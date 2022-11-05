# Chapter 1 Exercises

Exercises with a tick mark :ballot_box_with_check: represent exercises that must be submitted as part of your Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a _**new project**_ with the name of the exercise and save it to this exercises folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.  


&nbsp;

## Exercise 1: Print Strings :ballot_box_with_check:

Write a Python program to print the following string in a specific format.

Twinkle, twinkle, little star,
	How I wonder what you are! 
		Up above the world so high,   		
		Like a diamond in the sky. 
Twinkle, twinkle, little star, 
	How I wonder what you are

&nbsp;
&nbsp;
&nbsp;
## Exercise 2: Print the Version of Python :ballot_box_with_check:

 Write a Python program to get the Python version you are using.


&nbsp;
&nbsp;
&nbsp;
## Exercise 3: Print date and Time :ballot_box_with_check:

Write a Python program to display the current date and time.

&nbsp;
&nbsp;
&nbsp;

## Exercise 4: Strings Concatination :ballot_box_with_check:

Write three strings in different variables and print the output as one string.
&nbsp;
&nbsp;
&nbsp;

## Exercise 5: Compute area of Circle :ballot_box_with_check:

Write a Python program which accepts the radius of a circle from the user and compute the area.

&nbsp;
&nbsp;
&nbsp;

## Exercise 6: Arithmetic Operation :ballot_box_with_check:

Write a program to enter two integers and print their sum. (Addition)

&nbsp;
&nbsp;
&nbsp;

## Exercise 7: Arithmetic Operation :ballot_box_with_check:

Write a program to enter two integers and print their difference. (Subtraction)

&nbsp;
&nbsp;
&nbsp;

## Exercise 8: Arithmetic Operation  :ballot_box_with_check:

Write a program to enter two integers and print their product. (Multiplication)

&nbsp;
&nbsp;
&nbsp;

## Exercise 9: Arithmetic Operation  :ballot_box_with_check:

Write a program to enter two integers and print their quotient and remainder. (Division)

&nbsp;
&nbsp;
&nbsp;

## Exercise 10: Average and Percentage  :ballot_box_with_check:

Write a python program which accepts marks obtained in 5 subjects and calculate the average and percentage marks obtained in 5 subjects.

&nbsp;
&nbsp;
&nbsp;

# This is the solution of Chapter 1.

# Answer for Exercise 1 -

# Program – 
print("Twinkle, twinkle, little star, \n\tHow I wonder what you are! \n\t\tUp above the world so high, \n\t\tLike a diamond in the sky. \nTwinkle, twinkle, little star, \n\tHow I wonder what you are!")

# Output – 
Twinkle, twinkle, little star, 
	How I wonder what you are! 
		Up above the world so high, 
		Like a diamond in the sky. 
Twinkle, twinkle, little star, 
	How I wonder what you are!

# Answer for Exercise 2 -

# Program – 
import sys
print("Python version")
print (sys.version)

# Output – 
Python version
3.8.0 (tags/v3.8.0:fa919fd, Oct 14 2019, 19:37:50) [MSC v.1916 64 bit (AMD64)]

# Answer for Exercise 3 -

# Program - 
import datetime
now = datetime.datetime.now()
print("now=",now)
print ("Current date and time : ")
print (now.strftime("%Y-%m-%d %H:%M:%S"))

# Output – 
now= 2022-10-08 12:17:28.817432
Current date and time : 
2022-10-08 12:17:28

# Answer for Exercise 4 - 

# Program –
a = 'hello' 
b = 'python'
c = 'here'
print(a + b + c)  # Prints without a space 
print(a,b,c)    # prints with space

# Output – 
hellopythonhere
hello python here 

# Answer for Exercise 5 -

# Program –
from math import pi
r = float(input ("Enter radius of circle : "))
print ("Area of the circle is: " + str(pi * r**2))

# Output – 
Enter radius of circle : 6
Area of the circle is: 113.09733552923255

# Answer for Exercise 6 -

# Program –
a= int(input("Enter the first number:"))
b= int(input("Enter the second number:"))
sum = a+b
print ("sum of the number=",sum)

# Output – 
Enter the first number:5
Enter the second number:7
sum of the number= 12

# Answer for Exercise 7 -

# Program –
a= int(input("Enter the first number:"))
b= int(input("Enter the second number:"))
sum = a--b
print ("sum of the number=",sum)

# Output – 
Enter the first number:80
Enter the second number:45
sum of the number= 35

# Answer for Exercise 8 -

# Program –
a= int(input("Enter the first number:"))
b= int(input("Enter the second number:"))
product = a*b
print ("product of the number=",product)

# Output – 
Enter the first number:30
Enter the second number:20
product of the number= 600

# Answer for Exercise 9 -

# Program –
a= int(input("Enter the first number:"))
b= int(input("Enter the second number:"))
sum = a/b
print ("sum of the number=",sum)

# Output – 
Enter the first number:8
Enter the second number:2
sum of the number= 4.0

# Answer for Exercise 10 -

# Program –
subject1 = int(input("Enter your English marks"))
subject2 = int(input("Enter your Business marks"))
subject3 = int(input("Enter your Marketing marks"))
subject4 = int(input("Enter your Accounts marks"))
subject5 = int(input("Enter your Informatics marks"))

sum = subject1+subject2+subject3+subject4+subject5
average = sum/5
percent = (sum/500)*100

print(end="Average Mark = ")
print(average)
print(end="Percentage Mark = ")
print(percent)

# Output – 
Enter your English marks78
Enter your Business marks88
Enter your Marketing marks91
Enter your Accounts marks80
Enter your Informatics marks97
Average Mark = 86.8
Percentage Mark = 86.8










