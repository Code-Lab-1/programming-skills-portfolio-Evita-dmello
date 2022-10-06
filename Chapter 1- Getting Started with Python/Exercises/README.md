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
3.7.0 (v3.7.0:1bf9cc5093, Jun 27 2018, 04:59:51) [MSC v.1914 64 bit (AMD64)]

# Answer for Exercise 3 -

# Program - 
import datetime
now = datetime.datetime.now()
print("now=",now)
print ("Current date and time : ")
print (now.strftime("%Y-%m-%d %H:%M:%S"))

# Output – 
now= 2022-09-24 22:25:01.382348
Current date and time : 
2022-09-24 22:25:01

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






