# Python Quiz: Module 2
#### Formatting and Files
---
1. Which of the following code snippets will raise an error message assuming no variable assignments?
    - ( ) A. `print("Hello " + "Friend")`
    - ( ) B. `print('Hello','Friend')`
    - (x) C. `print("Hello", Friend)`
    - ( ) D. `print("Hello, 'Friend'")`
2. The variables product and cost have been assigned values using this code:         `product:str = 'apple'`  
`cost:float = 1.39`  
Which of the following code snippets will raise and error message?
    - ( ) A. `print(product, cost)`
    - (x) B. `print(product + cost)`
    - ( ) C. `print(product + str(cost))`
    - ( ) D. `print(product, 'costs', cost)`
3. What type of error generated in question 2 above?
    - ( ) A. IndentationError
    - ( ) B. ValueError
    - (x) C. TypeError
    - ( ) D. SyntaxError
4. Based on the variables created in question 2, which of the four ways to format output is used to generate **This apple costs $1.39.**:   
`print(f'This {product} costs ${cost:.2f}.')`?
    - ( ) A. Formatting with a `%` operator
    - ( ) B. Formatting with `.format()`
    - (x) C. Formatting with and f-string
    - ( ) D. Formatting with concatenation
5. Based on the variables created in question 2, which of the four ways to format output is used to generate **This apple costs $1.39.**:  
`print("This {} costs ${:.2f}.".format(product,cost))`?
    - ( ) A. Formatting with a `%` operator
    - (x) B. Formatting with `.format()`
    - ( ) C. Formatting with and f-string
    - ( ) D. Formatting with concatenation
6. What is the purpose of the backslash in this code: `print('I\'m enjoying Python.')`?
    - ( ) A. English contractions require a backslash in Python
    - (x) B. When you enclose a string with single quotes you must escape apostrophes because they will be interpreted as quotes
    - ( ) C. Python strings that include an apostrophe must place a backslash in front of it
    - ( ) D. Backslashes make code look cleaner
7. Which characters  can be used to render single quotes, double quotes, newline and tab characters without using a backslash?
    - [x] A. """
    - [ ] B. &&&
    - [ ] C. +++
    - [x] D. '''
8. Using three string variables, **name, address, phone**, have been defined and there is a variable **file_ref** that points to an open file, which code snippets below will NOT be helpful in creating a CSV file?
    - [ ] A. `file_ref.write("{},{},{}\n".format(name,address,phone))`
    - [ ] B. `file_ref.write(f"{name},{address},{phone}\n")`
    - [x] C. `file_ref.write(name + address + phone + "\n")`
    - [x] D. `file_ref.write(name,address,phone,sep=',',"\n")`
9. Given code that sets the value of **val**, `val: float = 1000/3*2`, what is the number returned by this code: `print(1000/3*2:.2f)`?
    - (x) A. 1666.67
    - ( ) B. 1666.6666666666665
    - ( ) C. 1666.00
    - ( ) D. 1700.00
10. What output is expected and why, when running the following code:  
`msg: str`  
`msg += "hello"`  
`print(msg)`  
    - ( ) A. no output because `msg` is not assigned a value
    - (x) B. NameError because `msg` was not defined when string concatenation was attempted
    - ( ) C. **hello** was printed because `msg` contained "hello" before `print` was called
    - ( ) D. SyntaxError because the `+=` operator can only be used with numbers