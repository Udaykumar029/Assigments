## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Python  is general purpose programming language.it very easy and simple and less line of code as compare of other language.
write less coding and achieve more in very less time , As compare to other technologies developement effort is very less because of 
rich library support provided in Python

Q2. Why is Python called a dynamically typed language?

Some languages, such as C++ and Java, need to know what type every variable is when it’s compiled.
 Dynamically typed languages such as python will figure out the type during runtime.

Q3. List some pros and cons of Python programming language?

Pro's:
It's Simple.
It's Free.
It's Easy to Use.
It's Highly Compatible.
It is Object-Oriented.
It has Lots of Libraries.
It's Widely Applicable.

Con's:
Poor Memory Efficiency.
Database Access.
Weak in Mobile Computing.
Runtime Errors.

Q4. In what all domains can we use Python?

Data Science,Automation,Application Development,AI & Machine Learning, Audio/Video Applications,Desktop GUI

Q5. What are variable and how can we declare them?

Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, 
and the value to be assigned to the variable.
Declaration of a variable  statement used to specify the variable name and its data type.
Syntax:
variable_name = value

Q6. How can we take an input from the user in Python?

We can take an input from the user in python by using the method input().

Q7. What is the default datatype of the value that has been taken as an input using input() function?

By default, input returns a string(str).

Q8. What is type casting?

The conversion of one data type into the other data type is known as type casting 

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes we can take more than one input from the user using single input() function, By using these  split() method

Q10. What are keywords?

 keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.

We cannot use a keyword as a variable name, function name, or any other identifier.
 
Reason-Keywords are particular words that act as a key to a code.They are used to define the syntax and structure of the Python language

Q12. What is indentation? What's the use of indentaion in Python?

Indentation refers to the spaces at the beginning of a code line.

Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?

We can throw some output in python by using the PRINT statement.

Q14. What are operators in Python?

Operators are used to perform operations on variables and values like addition ,subtraction,multiplication etc.

Q15. What is difference between / and // operators?

/(float division)-this operator provides the output in floating number once after division.
//(floor division)-this operator provides the output without decimal number once after division.


Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
i='iNeuron'
print(i*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

i=int(input('please enter the number'))
if i%2==0:
    print('Entered number is even')
else:
    print('Entered number is odd')

Q18. What are boolean operator?
Boolean means a result that can only have one of two possible values: true or false. 

Q19. What will the output of the following?
```
1 or 0- True

0 and 0- False

True and False and True- False

1 or 0 or 0- True
```

Q20. What are conditional statements in Python?

A conditional statement  is used to handle conditions in your program. 
These statements guide the program while making decisions based on the conditions encountered by the program

Q21. What is use of 'if', 'elif' and 'else' keywords?

The if condition  makes a decision based on whether the condition is true or not. 
If the condition is true, it prints out the indented expression. If the condition is false, it skips printing the indented expression.
The if-else condition adds an additional step in the decision-making process compared to the simple if statement. The beginning of an if-else statement operates similar to a simple if statement; however, if the condition is false, instead of printing nothing, the indented expression under else will be printed.
When you run into a situation where you have several conditions, you can place as many elif conditions as necessary between the if condition and the else condition.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

i=int(input('please enter the age'))
if i>=18:
    print('i can vote')
else:
    print("i can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```