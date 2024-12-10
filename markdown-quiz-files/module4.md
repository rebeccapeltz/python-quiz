# Python Quiz: Module 4
### List of Lists
---
1. How can the PyCharm debugger help you as a developer?
    - [x] A. You can modify program data as the program is running.
    - [x] B. It allows you to step through your code to verify the flow.
    - [ ] C. It will correct all of your errors.
    - [x] D. You can see variable reference addresses.
2.  Which of the following actions take place when you open a file in write mode?
    - [x] A. If the file exists the data in it will be overwritten.
    - [x] B. If the file doesn't exist, a new one will be created.
    - [ ] C. If the file exists, new data will be written after the existing data.
    - [ ] D. If you have opened a file in write mode, you must close it and reopen it to continue writing to it.
3. Which of the following commands will allow you to write data to a file?
    - [ ] A. file = open(FILENAME, 'r')
    - [x] B. file = open(FILENAME, 'a')
    - [ ] C. file = open(FILENAME, 'l')
    - [x] D. file = open(FILENAME, 'w')
4. If `file` has been opened in read mode, which of the following will read one line of data at a time
    - ( ) A. `file.append`
    - ( ) B. `file.readlines`
    - ( ) C. `file.read`
    - (x) D. `file.readline`
5. What is the difference between `file.read()` and `file.readlines()`?
    - ( ) A. `file.read` reads one line at a time and `file.readlines()` counts the number of lines in the file
    - ( ) B. `file.read` reads the entire file as a string and `file.readlines()` counts the number of lines in the file
    - (x) C. `file.read` reads the entire file as a string and `file.readlines()` reads the entire file and segregates the file into separate lines
    - ( ) D. `file.read` reads a line at a time and `file.readlines()` reads the entire file 
6. Using `with open("hello.txt") as my_file:` guarantees which of the following after the block of code following the `:` is executed?
    - ( ) A. The program will automatically exit.
    - (x) B. The file will be automatically closed without writing `file.close()`.
    - ( ) C. The program will ignore any other command regarding the file.
    - ( ) D. The block of code must contain a `file.close()` statement.
7. Which if the following is a tuple?
    - ( ) A. {a: 1, b:2}
    - ( ) B. {'a', 1, 'b', 2}
    - (x) C. ('a', 1, 'b', 2)
    - ( ) D. ['a',1,'b',2]  

8. Which if the following is a list?
    - ( ) A. {a: 1, b:2}
    - ( ) B. {'a', 1, 'b', 2}
    - ( ) C. ('a', 1, 'b', 2)
    - (x) D. ['a',1,'b',2]   

9. Which if the following is a set?
    - ( ) A. {a: 1, b:2}
    - (x) B. {'a', 1, 'b', 2}
    - ( ) C. ('a', 1, 'b', 2)
    - ( ) D. ['a',1,'b',2]   

10.  Which if the following is a dictionary?
    - (x) A. {a: 1, b:2}
    - ( ) B. {'a', 1, 'b', 2}
    - ( ) C. ('a', 1, 'b', 2)
    - ( ) D. ['a',1,'b',2]  

11.  What is the use case for a tuple?
    - ( ) A. Working with a collection of data the needs to be changed frequently.
    - (x) B. Working with a collection of data from a database where you need to maintain integrity by enforcing nonmutability.
    - ( ) C. Working with a collection of data that must contain unique values.
    - ( ) D. Working with a collection of data that must be easy to look up using a unique key.

12.  What is the use case for a dictionary?
    - ( ) A. Working with a collection of data the needs to be changed frequently.
    - ( ) B. Working with a collection of data from a database where you need to maintain integrity by enforcing nonmutability.
    - ( ) C. Working with a collection of data that must contain unique values.
    - (x) D. Working with a collection of data that must be easy to look up using a  unique key.

13.  What is the use case for a list?
    - (x) A. Working with a collection of data the needs to be changed frequently.
    - ( ) B. Working with a collection of data from a database where you need to maintain integrity by enforcing nonmutability.
    - ( ) C. Working with a collection of data that must contain unique values.
    - ( ) D. Working with a collection of data that must be easy to look up using a  unique key.

14.  What is the use case for a set?
    - ( ) A. Working with a collection of data the needs to be changed frequently.
    - ( ) B. Working with a collection of data from a database where you need to maintain integrity by enforcing nonmutability.
    - (x) C. Working with a collection of data that must contain unique values.
    - ( ) D. Working with a collection of data that must be easy to look up using a  unique key.

15.  Python strings are mutable.
    - ( ) True
    - (x) False

16. Lists and Tuples are ordered collections.
    - (x) True
    - ( ) False

17. If `data_list = ['a', 'b', 'c'] which of the following will unpack the list?
    - [x] A. `e,f,g = data_list`
    - [x] B. `(e,f,g) = data_list`
    - [ ] C. `{e,f,g} = data_list`
    - [x] D. `[e,f,g] = data_list`

18. If you want to `split` a string from a CSV file in order to create a `list`, why
is it important to `strip` the string before splitting it?
    - ( ) A. The `split` function requires that you `strip` the string first.
    - (x) B. The CSV file will contain a `\n` at the end of the line and the `strip` function will remove it before separating the comma separated strings.
    - ( ) C. You must `strip` all data in order to create a `list`.
    - ( ) D. There's no need to `strip` a string unless it contains an extra blank space at the beginning or end of string.