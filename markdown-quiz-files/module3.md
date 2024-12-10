# Python Quiz: Module 3
### Creating a User Interface
---
1. Which of the following is NOT a Python Coding Standard?
    - ( ) A. Python code should be indented 4 spaces.
    - ( ) B. Comments should be clear, concise, and meaningful.
    - (x) C. Python scripts should contain at least 100 lines of code.
    - ( ) D. Each line of code should be no longer than 79 characters.
2.  Which of the following are IDEs?
    - [x] A. Jupyter Notebook and Lab
    - [x] B. Idle
    - [ ] C. Microsoft Word
    - [x] D. Pycharm
3. Executing a script containing just pseduo code will produce the same results as Python in your IDE.
    - ( ) True
    - (x) False
4. `x = True` produces the same result as `x == True` in your Python script.
    - ( ) True
    - (x) False
5. The following code will produce an error:
    `name:str`  
    `print(name)`  
    - (x) True
    - ( ) False
6. The following code will produce an error: 
    `name:str = str()`  
    `print(name)`  
    - ( ) True
    - (x) False
7. What will be the output of executing the following code:
<pre><code>
name: str = 'John'
name = name.upper() 
if (name == 'John'):
    print('John') 
else:
    print(name)
</code></pre>
<br/>
    - ( ) A. john
    - ( ) B. John
    - ( ) C. JohN
    - (x) D. JOHN  

8. What will be the output of the following code?
<pre><code>
my_object_1 = None
my_object_2 
if (my_object_1 == my_object_2):
    print("Equal")
else:
    print("Not equal")
</code></pre>
<br/>
    - ( ) A. Equal  
    - ( ) B. Not equal  
    - ( ) C. TypeError  
    - (x) D. Name Error   

9. What will be the output of the following code?
<pre><code>
thing1: str = "abc"
thing2: str = "wxyz"
print(thing1 < thing2)
</code></pre>
<br/>
    - (x) A. True 
    - ( ) B. False 
    - ( ) C. abc  
    - ( ) D. wxyz  

10. Which operators are overloaded for string? 
    - [x] A. +
    - [ ] B. -
    - [x] C. *
    - [ ] D. %  

11. BONUS Given the code below, choose which statements will show all the methods for a string object.
<pre><code>
thing1: str = "abc"
</code></pre>
<br/>

    - [x] A. print(dir(thing1))
    - [ ] B. print(help(thing1))
    - [x] C. print(help(str))
    - [ ] D. print(dir(str))