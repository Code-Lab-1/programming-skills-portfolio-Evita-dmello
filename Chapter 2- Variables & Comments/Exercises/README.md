# Chapter 2 Exercises

Exercises with a tick mark :ballot_box_with_check: represent exercises that must be submitted as part of your Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a _**new project**_ with the name of the exercise and save it to this exercises folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.  


&nbsp;

## Exercise 1: Variables :ballot_box_with_check:

Type out the code below and add the correct data types to complete the variables

Assign a message to a variable, and print that message.
Then change the value of the variable to a new message, and print the new
message.

&nbsp;
&nbsp;
&nbsp;
## Exercise 2: Variables :ballot_box_with_check:

Find a quote from a famous person you admire. Print the quote and the name of its author. 

Your output should look something like the following, including the quotation marks:

Albert Einstein once said, “A person who never made a mistake never tried anything new.


&nbsp;
&nbsp;
&nbsp;
## Exercise 3: Stripping Names :ballot_box_with_check:

Tidy up the code to make it easier to understand

Use a variable to represent a person’s name, and include some whitespace characters at the beginning and end of the name. Make sure you use each character combination, “\t” and “\n”, at least once.

Print the name once, so the whitespace around the name is displayed. 

Then print the name using each of the three stripping functions, lstrip(), rstrip(), and strip().


&nbsp;
&nbsp;
&nbsp;

## Exercise 4: Favorite Number :ballot_box_with_check:
Use a variable to represent your favorite number. Then,using that variable, create a message that reveals your favorite number. Print
that message.

&nbsp;
&nbsp;
&nbsp;

## Exercise 5: USB Shopper :ballot_box_with_check:

A girl heads to a computer shop to buy some USB sticks. She loves USB sticks and wants as many as she can get for £50. They are £6 each.

Write a programme that calculates how many USB sticks she can buy and how many pounds she will have left.

You will to use the arithmetic operators to complete this exercise.

&nbsp;
&nbsp;
&nbsp;

## Exercise 6: Tip Calculator :ballot_box_with_check:

When you go out to eat, you always tip 20% of the bill amount. But who’s got the time to calculate the right tip amount every time? Write a program to calculate tips and save some time.
The program needs to take the bill amount as input and output the tip as a float.


&nbsp;
&nbsp;
&nbsp;

## Exercise 7: Working with Input :ballot_box_with_check:

Write a program to take x and y as input and output the string x, repeated y times.

&nbsp;
&nbsp;
&nbsp;

## Exercise 8: Area of Rectangle :ballot_box_with_check:

Write a program to find the area of a rectangle by taking the numbers from the user.

&nbsp;
&nbsp;
&nbsp;

## Exercise 9: In - place operators :ballot_box_with_check:

Solve the following in-place operators by using any of the numerical operation (+, -, *, /, %, **, //).

&nbsp;
&nbsp;
&nbsp;

## Exercise 10: Printing your Information :ballot_box_with_check:

Write a program to print your basic information.

&nbsp;
&nbsp;
&nbsp;

# This is the solution of Chapter 2.

# Answer for Exercise 1 -

# Program – 
message = "Python is very interesting."
print(message)

message = "I love learning it!"
print(message)

# Output – 
Python is very interesting.
I love learning it!

# Answer for Exercise 2 -

# Program – 
print ('A.P.J. Abdul Kalam once said, "Dreams is not what you see in sleep, is the thing which doesnot let you sleep."')

# Output – 
A.P.J. Abdul Kalam once said, "Dreams is not what you see in sleep, is the thing which doesn’t let you sleep."

# Answer for Exercise 3 -

# Program - 
name = "\tEvita Dmello\n"

print("Unmodified:")
print(name)

print("\nUsing lstrip():")
print(name.lstrip())

print("\nUsing rstrip():")
print(name.rstrip())

print("\nUsing strip():")
print(name.strip())

# Output – 
Unmodified:
	Evita Dmello


Using lstrip():
Evita Dmello


Using rstrip():
	Evita Dmello

Using strip():
Evita Dmello

# Answer for Exercise 4 - 

# Program –
fav_number = 3
message = "My favorite number is " + str(fav_number) + "."
print(message)

# Output – 
My favorite number is 3.

# Answer for Exercise 5 -

# Program –
money = 50
usb_price = 6
usb = money/usb_price
pounds_left = money%usb_price
print(usb)
print(pounds_left)

# Output – 
8.333333333333334
2

# Answer for Exercise 6 -

# Program –
bill = int(input("please enter the amount"))
x=20
y=100
tip=(bill*int(x)/int(y))
print(float(tip))

# Output – 
please enter the amount80
16.0

# Answer for Exercise 7 -

# Program –
x = str(input("Please enter a message"))
y = int(input("Please enter a number"))
print(x * y)

# Output – 
Please enter a message Python is fun
Please enter a number 4
Python is fun Python is fun Python is fun Python is fun
 
# Answer for Exercise 8 -

# Program –
width = int(input("Please enter a number"))
height = int(input("Please enter a number"))
area = int(width) * int(height)
print(area)

# Output – 
Please enter a number 9
Please enter a number 8
72

# Answer for Exercise 9 -

# Program –
x = 8

x -= 2
print(x)

x /= 3
print(x)

x **= 5
print(x)

x+=8
print(x)

x*=2
print(x)

x%=64
print(x)

x//=40
print(x)

# Output – 
6
2.0
32.0
40.0
80.0
16.0
0.0

# Answer for Exercise 10 -

# Program –
name = "Evita D Mello"
age= "18"
contact_number= "0560000000"
email = "evitadmello@gmail.com"
department= "Creative Computing"
level= "Bachelors"

print(name)
print(age)
print(contact_name)
print(email)
print(department)
print(level)

# Output
Evita D Mello
18
0560000000
evitadmello@gmail.com
Creative Computing
Bachelors

ex






