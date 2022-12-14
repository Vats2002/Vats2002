Q1. What is the purpose of Python's OOP?

ans1. In Python, object-oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. 
      It aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming

Q2. Where does an inheritance search look for an attribute?

ans2.An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher 
      superclasses, progressing from left to right (by default). The search stops at the first place the attribute is found.

Q3. How do you distinguish between a class object and an instance object?

ans3. A class is a template for creating objects in a program, whereas the object is an instance of a class. A class is a logical entity, while an object is a physical entity. 
      A class does not allocate memory space; on the other hand, an object allocates memory space.

Q4. What makes the first argument in a class’s method function special?

ans4. meth(args) becomes Class.
This is the reason the first parameter of a function in class must be the object itself. Writing this parameter as self is merely a convention. It is not a keyword and has no special meaning in Python.

Q5. What is the purpose of the init method?

ans5. The __init__ method lets the class initialize the object's attributes and serves no other purpose. It is only used within classes.

Q6. What is the process for creating a class instance?

ans6. The new operator requires a single, postfix argument: a call to a constructor. The name of the constructor provides the name of the class to instantiate.
       The new operator returns a reference to the object it created.

Q7. What is the process for creating a class?

ans7.Create a Class. To create a class, use the keyword class.
     Create Object. Now we can use the class named MyClass to create objects.
     The self Parameter.
     Modify Object Properties.
     Delete Object Properties.
     Delete Objects.

Q8. How would you define the superclasses of a class?

ans8. A superclass is the class from which many subclasses can be created. The subclasses inherit the characteristics of a superclass. The superclass is also known as the parent class or base class.

Q9. What is the relationship between classes and modules?

ans9. Modules are collections of methods and constants. They cannot generate instances. Classes may generate instances (objects), and have per-instance state (instance variables).

Q10. How do you make instances and classes?

ans10. To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q11. Where and how should be class attributes created?

ans11. Class attributes are the variables defined directly in the class that are shared by all objects of the class. Instance attributes are attributes or properties attached to an instance of a class.
        Instance attributes are defined in the constructor. Defined directly inside a class.

Q12. Where and how are instance attributes created?

ans12. Instance attributes are defined in the constructor. Defined directly inside a class. Defined inside a constructor using the self parameter.

Q13. What does the term "self" in a Python class mean?

ans13. The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class.

Q14. How does a Python class handle operator overloading?

ans14. The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. Such as, we use the "+" operator for adding two integers as well as joining two strings
        or merging two lists. We can achieve this as the "+" operator is overloaded by the "int" class and "str" class.

Q15. When do you consider allowing operator overloading of your classes?

ans15. Ensures that objects of a class behave consistently with built-in types and other user-defined types. Makes it simpler to write code, especially for complex data types. Allows for code reuse by implementing one operator method and using it for other operators.

Q16. What is the most popular form of operator overloading?

ans16.A very popular and convenient example is the Addition (+) operator. Just think how the '+' operator operates on two numbers and the same operator operates on two strings. It performs “Addition” on numbers whereas it performs “Concatenation” on strings.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

ans17.Both inheritance and polymorphism are fundamental concepts of object oriented programming. These concepts help us to create code that can be extended and easily maintainable.

Q18. Describe three applications for exception processing.

ans18.Integrating with external systems can introduce additional problems such as network errors involving firewalls, incorrect authentication or credentials, or system failures. An application that handles exceptions properly is critical to the success of any application.
      Many service types, including SOAP, have an exceptions or faults tab where you can define what the application does when a service error or exception is encountered. When the service encounters a processing error, and a condition evaluates to true, the application returns 
      a defined error message to the calling application. The following conditions are available for defining an error response message.

Q19. What happens if you don't do something extra to treat an exception?

ans19.if you don't handle exceptions
      When an exception occurred, if you don't handle it, the program terminates abruptly and the code past the line that caused the exception will not get executed.

Q20. What are your options for recovering from an exception in your script?

ans20.You can also provide a generic except clause, which handles any exception. After the except clause(s), you can include an else-clause. The code in the else-block executes if the code in the try: block does not raise an exception. The else-block is a good place for code that does not need the try: block's protection.

Q21. Describe two methods for triggering exceptions in your script.

ans21.To avoid such a scenario, there are two methods to handle Python exceptions: Try – This method catches the exceptions raised by the program. Raise – Triggers an exception manually using custom exceptions.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of
whether or not an exception exists.

ans22.The code within the try clause will be executed statement by statement. If no exception occurs during the execution, the execution will reach the break statement and the while loop will be left.

Q23.What is the purpose of the try statement?

ans23.The try statement allows you to define a block of code to be tested for errors while it is being executed. The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

Q24. What are the two most popular try statement variations?

ans24.The Different Try/Except Variations. So far we've used a try / except and even a try / except / except , but this is only two-thirds of the story. There are two other optional segments to a try block: else and finally . Both of these optional blocks will come after the try and the except .

Q25. What is the purpose of the raise statement?

ans25.The RAISE statement stops normal execution of a PL/SQL block or subprogram and transfers control to an exception handler. RAISE statements can raise predefined exceptions, such as ZERO_DIVIDE or NO_DATA_FOUND , or user-defined exceptions whose names you decide.

Q26. What does the assert statement do, and what other statement is it like?

ans26.The assert keyword is used when debugging code. The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError. You can write a message to be written if the code returns False.

Q27. What is the purpose of the with/as argument, and what other statement is it like?

ans27.The with statement is a replacement for commonly used try/finally error-handling statements. A common example of using the with statement is opening a file. To open and write to a file in Python.

Q28. What are *args, **kwargs?

ans28.*args specifies the number of non-keyworded arguments that can be passed and the operations that can be performed on the function in Python whereas **kwargs is a variable number of keyworded arguments that can be passed to a function that can perform dictionary operations.

Q29. How can I pass optional or keyword parameters from one function to another?

ans29.Users can either pass their values or can pretend the function to use theirs default values which are specified. In this way, the user can call the function by either passing those optional parameters or just passing the required parameters. Without using keyword arguments. By using keyword arguments.

Q30. What are Lambda Functions?

ans30.Lambda functions are intended as a shorthand for defining functions that can come in handy to write concise code without wasting multiple lines defining a function. They are also known as anonymous functions, since they do not have a name unless assigned one.

Q31. Explain Inheritance in Python with an example?

ans31.Inheritance relationship defines the classes that inherit from other classes as derived, subclass, or sub-type classes. Base class remains to be the source from which a subclass inherits. For example, you have a Base class of “Animal,” and a “Lion” is a Derived class. The inheritance will be Lion is an Animal.

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?

ans32.A class definition, where a child class SubClassName inherits from the parent classes BaseClass1, BaseClass2, BaseClass3, and so on, looks like this:

class SubclassName(BaseClass1, BaseClass2, BaseClass3, ...):
    pass
It's clear that all the superclasses BaseClass1, BaseClass2, BaseClass3, ... can inherit from other superclasses as well. What we get is an inheritance tree.

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

ans33.Using isinstance() function, we can test whether an object/variable is an instance of the specified type or class such as int or list. In the case of inheritance, we can checks if the specified class is the parent class of an object.

Q34.Explain the use of the 'nonlocal' keyword in Python.

ans34.The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. Use the keyword nonlocal to declare that the variable is not local.

Q35. What is the global keyword?
ans35.The global keyword is used to create global variables from a no-global scope, e.g. inside a function.