# Python Quiz: Module 7

#### Modularization: Separation of Concerns
---
1. Which function definition below produces an instance of a Dog encapsulating breed and color of the dog?
    - ( ) A. `def new_dog(breed:str,color:str):`
    - ( ) B. `class Dog:`
    - (x) C. `def __init__(self, breed: str = "", color: str = ""):`
    - ( ) D. ` def __str__(self):`

2. What does a class constructor do?
    - [x] A. Assign data values to class attributes
    - [x] B. Create an instance of the class
    - [x] C. Create an object
    - [ ] D. Print out attribute data from the class

3. How can class attributes be accessed?
    - [x] A. From an instance of a class
    - [x] B. From a function within the class
    - [x] C. From a function decorated with @property
    - [ ] D. From a static method defined inside the class

4. From which base class do all new classes inherit from?
    - ( ) A. `Object`
    - ( ) B. `class`
    - (x) C. `object`
    - ( ) D. `Class`

5. You are designing a medical application. You have developed a class `Person` that contains data about an individual, like Name, Address, Phone, Insurance.  You are now tasked with developing a class name `Medication` that inherits from Person that will include attributes about the medications that the person is using. Which of the following code could be used to  define the Medication class?
    - ( ) A. `def Person(Medication):`
    - ( ) B. `def Medication(Person):`
    - (x) C. `class Medication(Person):`
    - ( ) D. `class Person(Medication):`

6. Which if the following is a decoration that run code to validate and assign data to a class attribute?
    - ( ) A. `@setter`
    - ( ) B. `@setter.property`
    - ( ) C. `@property.setter`
    - (x) D. `@<attribute name>.setter`

7. Which of the following describes "overriding" in Python?
    - [x] A. A way to bring about polymorphism
    - [ ] B. Adding new parameters to a function in a subclass
    - [x] C. Re-implementing a method in a subclass to provide more specific functionality
    - [ ] D. Adding new arguments to functions that interact with an instance of the class
    
8. Which of the following are true about Git and GitHub  
    - [ ] A. Git has a web interface.
    - [x] B. Git is a version control tool can be installed locally.
    - [ ] C. GitHub is a command line tool.
    - [x] D. GitHub is a cloud based service that runs Git.

9. Which of the following is true about a Python statement?
    - [ ] A. It always returns a value.
    - [x] B. It is a line a code that executes an action.
    - [ ] C. It always prints output in the console.
    - [x] D. It is the smallest unit of code the Python interpreter can execute.

10. What is the purpose of creating multiple different classes instead of one big class that contains all the code in the different classes?
    - [x] A. By defining different classes you can control access to individual attributes better via encapsulation.
    - [ ] B. Python has a limit on the size of file it can interpret.
    - [x] C. Modularity makes the code more focused and easy to understand.
    - [ ] D. There is a limit to the number of classes you can put into a single file in Python.