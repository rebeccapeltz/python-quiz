# Python Quiz: Module 5

#### List of Dictionaries
---
1. Which of the following code snippets describe an ordered collection of data in Python?
    - [x] A. `['d','a','f']`
    - [x] B. `'abc'`
    - [ ] C. `{'a','b','c'}`
    - [x] D. `{'first_name':'Rudolph','last_name':'Reindeer','age':5}`
  
2.  Which of the following words is used to describe a collection?
    - ( ) A. Category
    - ( ) B. Cluster
    - (x) C. Container
    - ( ) D. Cluster
   
3. Which code snipped can be used to access the letter `s` from a variable named `level` referencing the string `basic`?
    - ( ) A. `level(3)`
    - ( ) B. `level[3]`
    - ( ) C. `level(2)`
    - (x) D. `level[2]`
    
4. What is the value of the variable `output` after running this code 
`output = '1,2,3'.split(',')`?
    - ( ) A. ('1', '2', '3')
    - (x) B. ['1', '2', '3']
    - ( ) C. {'1', '2', '3'}
    - ( ) D. '123'

5. If you have a tupple named `colors` which contains `('white','red','green')`, how do you access the color `red` from the tupple?
    - (x) A. `colors[1]`
    - ( ) B. `colors{1}`
    - ( ) C. `colors(1)`
    - ( ) D. `colors[2]`
   
6. The following code describes the assignment of a dictionary to a variable: `my_dict = {'day':'Tuesday','weather':'snow','temp':'32F'}`.  Which of the code snippets below can be used to convert the dictionary into 3 string variables: `day_of_week,precipitation,temperature`?

    - ( ) A. `day_of_week,precipitation,temperature = my_dict`
    - ( ) B. `day_of_week,precipitation,temperature = my_dict[1,2,3]`
    - ( ) C. `day_of_week,precipitation,temperature = my_dict.split(',')`
    - (x) D. `day_of_week,precipitation,temperature = my_dict.values()`


7. After opening a CSV file with read mode, you read the data one `row` at time with `for row in file.readlines():`. You want to convert each `row` from a csv string terminated by a newline into a list of strings.  Which code snippet can you use to convert the `row` from a string with a newline into a list of data strings.
    - ( ) A. `row = row.split(',')`
    - ( ) B. `row = row.strip(',')`
    - (x) C. `row = row.strip().split(',')`
    - ( ) D. `row = row.split(').strip()`

8. If you want raise an exception when a user has chosen option 5, but you only support options 1-4, how will you code this? 
    - [ ] A. `raise FileNotFoundError("Enter a number between 1 and 4")`
    - [x] B. `raise Exception("Enter a number between 1 and 4")`
    - [ ] C. `raise TypeError("Enter a number between 1 and 4")` 
    - [x] D. `raise ValueError("Enter a number between 1 and 4")`    

9. When will the code following `except FileNotFoundError as e:` be executed?
    - ( ) A. When the program tries to close a file that hasn't been opened.
    - ( ) B. When the program detects the user is trying close a file that they removed in code. 
    - ( ) C. When the program attempts to close a file that is already closed.
    - (x) D. When the program attempts to open a file using a path that doesn't exist.

10.  What is the purpose of `finally` in Python exception handling?
    - ( ) A. Informs the user that the program is ending.
    - ( ) B. Only performs cleanup when an exception has been raised in a code block.
    - (x) C. Perform cleanup such as closing files whether there are exceptions or not.
    - ( ) D. It clears all variable references.

