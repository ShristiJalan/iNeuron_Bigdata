###### Q1. Why do we call Python as a general purpose and high-level programming language?

Python is called as general purpose programming language as it is used for building software in a wide variety of applications.
It is also known as high-level programming language as it is easy for humans to understand.

###### Q2. Why is Python called a dynamically typed language?

As it doesn’t know about the type of the variable until the code is run. So declaration is of no use.

###### Q3. List some pros and cons of Python programming language?

Pros 
- Beginner Friendly
- Flexible and Extensible
- Highly Scalable
- IOT Opportunities
- Machine Learning
- Portable
 
Cons 
- Slower than compiled languages
- Security
- Work Environment
- Python's memory consumption and garbage consumption
- Multithreading in Python

###### Q4. In what all domains can we use Python?

Web Development, Data Science, Artificial Intelligence and Machine Learning, Game Development, Software Development.

###### Q5. What are variable and how can we declare them?

Variables are the basic unit of storage in a programming language. In order to declare a variable, the variable name, and the value has to be assigned to the variable. 

###### Q6. How can we take an input from the user in Python?

using input() function we can take input from user in python. 
username = input("Enter username:")
print("Username is: " + username)

###### Q7. What is the default datatype of the value that has been taken as an input using input() function?

string data type

###### Q8. What is type casting?

Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

###### Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Yes, using split()
x, y = input("Enter two values: ").split()
print("Number of boys: ", x)
print("Number of girls: ", y)

###### Q10. What are keywords?

Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes. These keywords are always available—you'll never have to import them into your code. 

###### Q11. Can we use keywords as a variable? Support your answer with reason.
No we cannot use keyword as a variable name, as the keywords are specially reserved words and it has some specific meaning and purpose.

###### Q12. What is indentation? What's the use of indentaion in Python?

Python indentation is a way of telling a Python interpreter that the group of statements belongs to a particular block of code.

###### Q13. How can we throw some output in Python?

Using print() we can print the output in python.

###### Q14. What are operators in Python?

In Python, operators are special symbols that designate that some sort of computation should be performed.

###### Q15. What is difference between / and // operators?

In Python programming, you can perform division in two ways. The first one is Float Division("/") and the second is Integer Division("//") or Floor Division.
5/2 = 2.5
5//2 = 2

###### Q16. Write a code that gives following as an output.
###### iNeuroniNeuroniNeuroniNeuron

a = "iNeuron"
print(a+a+a+a)

###### Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

a = input("Enter a number: ")
if(a%2 == 0):
    print("even")
else:
    print("odd")

###### Q18. What are boolean operator?

There are three logical operators that are used to compare values. They evaluate expressions down to Boolean values, returning either True or False . These operators are and , or , and not 