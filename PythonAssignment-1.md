## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
 
ans1.  Python is called general purpose because it can used to design and develop a wide variety of applications, across multiple domain. High-level programming language means it's more user-friendly.

Q2. Why is Python called a dynamically typed language?

ans2. Dynamically typed language means that variables are checked against types only when the program is executing. We don't need to declare the variable type, the interpreter automatically interprets it.

Q3. List some pros and cons of Python programming language?

ans3.  Pros:

     Easy to use
     Easy to integrate
     Multi-paradigm approach
     High library support

       Cons:

     Slow speed of execution compared to C,C++
     Absence from mobile computing and browsers


Q4. In what all domains can we use Python?

ans4. Graphic design, image processing applications, Games, and Scientific/ computational Applications
      Web frameworks and applications
      Database Access
      Language Development
      Prototyping
      Software Development
      Scripting

Q5. What are variable and how can we declare them?

Variable are the name which  was given to a memory location.
we declare variable like  type_variablename = value; where type is one of c types(such as int),for ex; int_var = 10


Q6. How can we take an input from the user in Python?

ans6. we can use input() function


Q7. What is the default datatype of the value that has been taken as an input using input() function?

ans7. By default , input returns string

Q8. What is type casting?

ans8. type casting is the process in which the compiler automatically converts one data type in a program to another one.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

ans9. Yes, we can take more than one input from using single input
      
     a, b , c = input("Enter three values: ").split(",")
     print("Total number of students: ", a)
     print("Number of boys is : ", b)
     print("Number of girls is : ", c)
     print()
     a = [int(a) for a in input("Enter multiple value: ").split(",")]
     print("Number of list is: ", a) 


Q10. What are keywords?

ans10. Keywords are special reserved words that have specific meaning and purposes and can't be used for anything but those specific purposes.
       These keywords are available -we never have to import them into our code.python keywords are different from python's built-in functions and types.
       some keywords are- true,and,else,from,while,with,not etc.

Q11. Can we use keywords as a variable? Support your answer with reason.

ans11.  Yes we can but we shoudn't as it will override the properties of the keyword.

Q12. What is indentation? What's the use of indentaion in Python?

ans12.Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only,
the indentation in Python is very important. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?

ans13.  using print()function.

Q14. What are operators in Python?

ans14. Symbols or keywords used to perform certain operations on values or variable are known as operators. There are different types of operators like

       Arithmetic operators
       Comparison Operators
       Logical Operators
       Bitwise Operators
       Assignment Operators

Q15. What is difference between / and // operators?

ans. / is used for float division and // is used of floor (integer) division.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
ans16. str_data ="ineuron"
       empty_str = ""

       full_name = str_data +""+"ineuron"+"ineuron"+"ineuron"
       print("full_name=",full_name)

       output is iNeuroniNeuroniNeuroniNeuron

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

ans17. num = float(input("Enter a number: "))
      if num%2 == 0:
        print(f"{num} is even")
      else:
        print(f"{num} is odd")


Q18. What are boolean operator?

ans18. The logical operators and, or and not are also referred to as boolean operators. While and as well as or operator needs two operands,
       which may evaluate to true or false, not operator needs one operand evaluating to true or false. Boolean and operator returns true if both operands return true.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
ans19.     1 or 0
           0 and 0

Output:    1 or 0 -> 1
          0 and 0 -> 0
         True and False and True -> False
          1 or 0 or 0 -> 1
           

Q20. What are conditional statements in Python?

ans20. A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions. encountered by the program
        Python has 3 key Conditional Statements that you should know: if statement. if-else statement


Q21. What is use of 'if', 'elif' and 'else' keywords?

ans21.  if is the first condition check for the condition.

      if "if" is False then elif's condition is checked.

      else is checked when all the upper condition fails.
     

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

ans22.  age = int(input("Enter you age: "))
        if age >= 18:
            print("I can vote")
       else:
            print("I can't vote") 

      

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ans.   int_even = 0

       numbers = [12, 75, 150, 180, 145, 525, 50]
       for i in numbers:
        if (i%2==0):
            print(i,"is even")
            int_even = int_even +i
       print("total sum of elements=",int_even)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

ans24. num1 = 10
       num2 = 14
       num3 = 12

    if (num1 >= num2) and (num1 >= num3):
      greatest = num1
   elif (num2 >= num1) and (num2 >= num3):
      greatest = num2
   else:
      greatest = num3

print("The greatest number is", greatest)



Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ans25. numbers = [12, 75, 150, 180, 145, 525, 50]
       b = []
       for i in a:
          if i > 150:
              if i > 500:
                  break
              continue
       if i % 5 == 0:
           b.append(i)
        
       print(b)