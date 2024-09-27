# Markdown Quiz Generator

This repository using code found in this repository: https://github.com/osandadeshan/markdown-quiz-generator.  

I acknowledge the source of this code by including the original License in this repository.

## Install Python

Install Python and the pip package manager. Once python is installed you can install the libraries using the requirements.txt.

`pip install -r requirements.txt`

If you're using a virtual environment you can execute these commands:

```
python3 -m venv <name of environment>
source <name of environment>/bin/activate
pip install -r requirements
```


## Quiz structure (Markdown) 
Although it is based on markdown for its style format, at the moment the following types of questions are supported:

1. **Question of a selection**:
```text
1. MaxSoft is a software company.
    - (x) True
    - ( ) False
```
```text
2. The domain of MaxSoft is test automation framework development.
    - (x) True
    - ( ) False 
```
Note that the correct answer is specified with an **x** ( x or X, upper or lower case) and must be in parentheses to specify that it is only one to be selected, for example, for false or true questions.

2. **Multiple selection question**:
```text
3. What are the test automation frameworks developed by MaxSoft?
    - [x] IntelliAPI
    - [x] WebBot
    - [ ] Gauge
    - [ ] Selenium
```
Very similar to the previous one but this type of question allows you to select more than one at a time, they must be in square brackets with an **x** to the correct answers. The result to these types of questions is prorated, that is, you must select only the correct ones so that that question is interpreted as correct.

Note that for questions types 1 and 2, you must leave a space for the wrong answers, eg. () or [], the questions must be multiple selection or a selection, you cannot mix them.

3. **Open question** (Enter text)
```text
4. Who is the Co-Founder of MaxSoft?
    - R:= Osanda
```
It is a question where you must write the correct answer, this is specified in the following line of the question preceded by **R: =** (R or, upper or lower case) then the correct answer (it is validated regardless of whether it is uppercase or lowercase)


## Generating quizzes
The application will generate all the **.md** (Markdown) files that are inside the folder 
`./markdown-quiz-files/**`. Note that this folder already has a default quiz (sample-quiz.md).

You can add as many as Markdown files you want, and each of them will generate a separate quiz.

To generate quizzes run `python quiz-generator.py`.  Markdown in the markdown-quiz-files will be converted to HTML in the `generated-quizzes`directory.

## Serving Quizzes

The `markdown-quiz-generator/index.html` file should be served.  You can start a local server to manually test your quizzes.  You must manually enter the quiz into the `index.html` file.  Style `index.html` file as needed.  You can add a quiz to the list of quizzes.

```html
<div class="container">
        <div class="form-row">
            <div class="container">
                <h1>Python Quizzes</h1>
                <div><a href="./module1.html">Module 1</a></div>
                <!-- add links to quizzes here -->
            </div>
        </div>
    </div>
```