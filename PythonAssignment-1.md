## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
 
ans1. Python is an  interpreted  language Because they are not written in machine readable language.Everytime a program is run,its interpreter rus through the code and translates it into machine readable byte code

Q2. Why is Python called a dynamically typed language?

ans2. Python called a dynamically typed language beacause the type of the variable is determined only during runtime.

Q3. List some pros and cons of Python programming language?

ans3.  Pros                                    cons
 -improved productivity                    -slow speed 
 -interpreted language                     -not memoryefficient 
 -dynamically typed                        -weak in mobile computing 
 -free and open source                     -database access
  vast library support                     -run time errors


Q4. In what all domains can we use Python?

ans4. python is used in artificial intelligence,machine learning,deep learning,desktop GUI,web devlopment,data analytics and data visualization.

Q5. What are variable and how can we declare them?

Variable are the name which  was given to a memory location.
we declare variable like  type_variablename = value; where type is one of c types(such as int),for ex; int_var = 10
float_var = 18.25

Q6. How can we take an input from the user in Python?

ans6. we can use input() function

     name = input()
     age = input()
     print("User name = ",name)
     print("User age = ",age)

Q7. What is the default datatype of the value that has been taken as an input using input() function?

ans7. By default , input returns string

Q8. What is type casting?

ans8. type casting is the process in which the compiler automatically converts one data type in a program to another one.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

ans9. Yes, we can take more than one input in one single line by using the raw_input function


Q10. What are keywords?

ans10. Keywords are special reserved words that have specific meaning and purposes and can't be used for anything but those specific purposes.
       These keywords are available -we never have to import them into our code.python keywords are different from python's built-in functions and types.
       some keywords are- true,and,else,from,while,with,not etc.

Q11. Can we use keywords as a variable? Support your answer with reason.

ans11. No,we can't use keywords as a variable Keywords are used to define the syntax of the coding.
       The keyword cannot be used as an variable name. All the keywords in python are written in lower case except True and False.

Q12. What is indentation? What's the use of indentaion in Python?

ans12.Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only,
the indentation in Python is very important. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?

ans13.    name="tushar"
          print("tushar")
          
         output = tushar

Q14. What are operators in Python?

ans14. In Python, operators are special symbols that designate that some sort of computation should be performed. The values that an operator acts on are called operands.
      Here is an example: >>> >>> a = 10 >>> b = 20 >>> a + b 30. In this case, the + operator adds the operands a and b together.

Q15. What is difference between / and // operators?

ans. The first one is Float Division("/") and the second is Integer Division("//") or Floor Division.Float Division("/"): Divides left hand operand by right hand operand.
    example:5/2 = 2.5 and Floor Division("//"): The division of operands where the result is the quotient in which the digits after the decimal point are removed. But if one 
    of the operands is negative, the result is floored , i.e., rounded away from zero (towards negative infinity) example:5//2 = 2.

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

ans.  for odd

      for num in range (1,11,2):
         print (num)

      output is 1,3,5,7,9


      for even no.

     for num in range (2,11,2):
         print (num)

      output is 2,4,6,8,10
+

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

Output:    1, 1
           1, 0

           true and true
           1 or 1

Q20. What are conditional statements in Python?

ans20. A conditional statement as the name suggests itself, is used to handle conditions in your program. These statements guide the program while making decisions based on the conditions. encountered by the program
        Python has 3 key Conditional Statements that you should know: if statement. if-else statement


Q21. What is use of 'if', 'elif' and 'else' keywords?

ans21. … elif…else are conditional statements that provide you with the decision making that is required when you want to execute code based on a particular condition.
        The if… elif…else statement used in Python helps automate that decision making process.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

ans22.  age = 18

      if age > 0:
         print("i can vote")

        output is i can vote

  >>>    age = 17

         if age < 18:
            print("i can't vote")

  >>>   output is i can't vote

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

       total sum of elements= 392

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

ans24. num1 = 10
       num2 = 14
       num3 = 12

    if (num1 >= num2) and (num1 >= num3):
      largest = num1
   elif (num2 >= num1) and (num2 >= num3):
      largest = num2
   else:
      largest = num3

print("The largest number is", largest)



Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
ans25. a = [12, 75, 150, 180, 145, 525, 50]
       b = []
       for i in a:
          if i > 150:
              if i > 500:
                  break
              continue
       if i % 5 == 0:
           b.append(i)
        
       print(b)