# Python Quiz: Module 6

### List of Objects: Object Oriented Programming
---
1. What is OOP encapsulation?
    - (x) A. The packaging together of properties and methods in order to provide controlled access to data.
    - ( ) B. The ability for child classes to override or overload base methods and thereby behave as a different type than its parent class.
    - ( ) C. The process of defining a base “parent” class containing attributes and methods which can be use to create a “child” class that uses the attributes and methods of the parent and can add new attributes and methods more specific to itself.
    - ( ) D. The process of simplifying interaction with a complex system.  Methods and property getters and setters provide an interface that shields the user from underlying code complexity.
  
2.  What is OOP polymorphism?
    - ( ) A. The packaging together of properties and methods in order to provide controlled access to data.
    - (x) B. The ability for child classes to override or overload base methods and thereby behave as a different type than its parent class.
    - ( ) C. The process of defining a base “parent” class containing attributes and methods which can be use to create a “child” class that uses the attributes and methods of the parent and can add new attributes and methods more specific to itself.
    - ( ) D. The process of simplifying interaction with a complex system.  Methods and property getters and setters provide an interface that shields the user from underlying code complexity.

3.  What is OOP abstraction?
    - ( ) A. The packaging together of properties and methods in order to provide controlled access to data.
    - ( ) B. The ability for child classes to override or overload base methods and thereby behave as a different type than its parent class.
    - ( ) C. The process of defining a base “parent” class containing attributes and methods which can be use to create a “child” class that uses the attributes and methods of the parent and can add new attributes and methods more specific to itself.
    - (x) D. The process of simplifying interaction with a complex system.  Methods and property getters and setters provide an interface that shields the user from underlying code complexity.

4.  What is OOP inheritance?
    - ( ) A. The packaging together of properties and methods in order to provide controlled access to data.
    - ( ) B. The ability for child classes to override or overload base methods and thereby behave as a different type than its parent class.
    - (x) C. The process of defining a base “parent” class containing attributes and methods that can be used to create a “child” class which uses the attributes and methods of the parent and can add new attributes and methods more specific to itself.
    - ( ) D. The process of simplifying interaction with a complex system.  Methods and property getters and setters provide an interface that shields the user from underlying code complexity.

5. Which of the following might be an instruction to instantiate a Shape object?
    - [ ] A. shape = new Shape('circle')
    - [x] B. shape = Shape()
    - [ ] C. shape = construct(Shape)
    - [x] D. shape = Shape(type='circle',diameter='5')

6. The following code defines an class that creates a bank account. Which 
code snippet instantiates a bank account object?
<pre><code>
class Person: 
    def __init__(self, first_name,last_name): 
        self.first_name = first_name 
        self.last_name = last_name       
    @staticmethod
    def print_grinning_face:
        print("\U0001F606")  
</code></pre>
<pre><code>
class Bank_Account(Person): 
    def __init__(self, first_name, last_name, account_number, balance): 
        super().__init__(first_name,last_name) 
        self.account_number = account_number 
        self.balance = balance   
    def deposit(self,amount): 
        self.balance += amount   
    def withdrawal(self,amount): 
        self.balance -= amount    
    @staticmethod 
    def advice(): 
        print("Save for a rainy day")  
</code></pre>  

    - ( ) A. bank_account = new Bank_Account()
    - (x) B. bank_account = Bank_Account('Vic','Vu',12345,1000.00)
    - ( ) C. bank_account = Bank_Account(12345,1000.00)
    - ( ) D. bank_account = Person('Vic','Vu',12345,1000.00)

7. Which of the following are examples of instance methods in the code above?
    - [x] A. `deposit`
    - [x] B. `withdrawal`
    - [ ] C. `print_grinning_face`
    - [ ] D. `advice`

8. Which of the following are examples of static methods in the Bank Account code?
    - [ ] A. `deposit`
    - [ ] B. `withdrawal`
    - [x] C. `print_grinning_face`
    - [x] D. `advice`

9. Which of the following are NOT properties in the Bank Account code?
    - [ ] A. account_number
    - [x] B. advice
    - [ ] C. last_name
    - [x] D. self

10. When a subclass overrides a parent class method, which of the following characteristics does it have?
    - [x] A. Same name as parent
    - [x] B. Same return type as the parent
    - [x] C. Same number of argments in the calling code
    - [ ] D. Same result as the parent

11. When a subclass overloads a parent class method, which of the following characteristics does it have?
    - [x] A. Same name as parent
    - [x] B. It relies on overriding default parameters
    - [ ] C. Same number of arguments as the parent
    - [ ] D. Same result as the parent

