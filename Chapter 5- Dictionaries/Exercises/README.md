# Chapter 5 Exercises

Exercises with a tick mark :ballot_box_with_check: represent exercises that must be submitted as part of your Programming Skills Portfolio as a minimum expectation. Completing more exercises provides the opportunity to attain higher marks. For each exercise you should create a _**new project**_ with the name of the exercise and save it to this exercises folder in your local repository.

Once you have completed your solution you should make sure you commit and push your solutions to your remote repository on GitHub. You can commit and push as many changes to your solutions as you wish, only those pushed before the chapter deadlines will be marked for the Programming Skills Portfolio.  

---
&nbsp;

## Exercise 1: Person :ballot_box_with_check:

Use a dictionary to store information about a person you know.Store their first name, last name, age, and the city in which they live. You

should have keys such as first_name, last_name, age, and city. Print each piece of information stored in your dictionary.

&nbsp;
&nbsp;

## Exercise 2: Glossary :ballot_box_with_check:

A Python dictionary can be used to model an actual dictionary. However, to avoid confusion, let’s call it a glossary.

* Think of five programming words you’ve learned about in the previous chapters. Use these words as the keys in your glossary, and store 

their meanings as values.

* Print each word and its meaning as neatly formatted output. You might print the word followed by a colon and then its meaning, or print 

the word on one line and then print its meaning indented on a second line. Use the newline character (\n) to insert a blank line between 

each word-meaning pair in your output.
&nbsp;
&nbsp;

## Exercise 3: Glossary 2 :ballot_box_with_check:
Now that you know how to loop through a dictionary, clean up the code from Exercise 6-3 (page 99) by replacing your series of print()

calls with a loop that runs through the dictionary’s keys and values. When you’re sure that your loop works, add five more Python terms 

to your glossary.When you run your program again, these new words and meanings should automatically be included in the output.

&nbsp;
&nbsp;

## Exercise 4: Rivers :ballot_box_with_check:

Make a dictionary containing three major rivers and the country each river runs through. One key-value pair might be 'nile': 'egypt'.

* Use a loop to print a sentence about each river, such as The Nile runs through Egypt.

* Use a loop to print the name of each river included in the dictionary.

* Use a loop to print the name of each country included in the dictionary.

&nbsp;
&nbsp;

## Exercise 5: Pets :ballot_box_with_check:

Make several dictionaries, where each dictionary represents a different pet. In each dictionary, include the kind of animal and the

owner’s name. Store these dictionaries in a list called pets. Next, loop through your list and asyou do, print everything you know about 

each pet



&nbsp;
&nbsp;


# This is the solution of Chapter 5.

# Answer for Exercise 1 -

# Program – 
person = {'first_name': 'evita','last_name': 'dmello','age': 18,'city': 'dubai'}

print(person['first_name'])
print(person['last_name'])
print(person['age'])
print(person['city'])

# Output –
evita
dmello
18
dubai

# Answer for Exercise 2 -

# Program – 
glossary = {
    'string': 'String is a collection of alphabets,words or other characters.',
    'variable': 'A python variable is a symbolic name that is a reference or pointer to an object.',
    'list': 'Lists are used to store multiple items in a single variable.',
    'loop': 'Python for loops are used to loop through an iterable object(like a list,tuple,set,etc)and perform the same action for each entry .',
    'dictionary': "Dictionaries are used to store data values in key:value pairs.",
    }

word = 'string'
print(f"\n{word.title()}: {glossary[word]}")

word = 'variable'
print(f"\n{word.title()}: {glossary[word]}")

word = 'list'
print(f"\n{word.title()}: {glossary[word]}")

word = 'loop'
print(f"\n{word.title()}: {glossary[word]}")

word = 'dictionary'
print(f"\n{word.title()}: {glossary[word]}")

# Output –
String: String is a collection of alphabets,words or other characters.

Variable: A python variable is a symbolic name that is a reference or pointer to an object.

List: Lists are used to store multiple items in a single variable.

Loop: Python for loops are used to loop through an iterable object(like a list,tuple,set,etc)and perform the same action for each entry .

Dictionary: Dictionaries are used to store data values in key:value pairs.

# Answer for Exercise 3 -

# Program –
glossary = {
    'string': 'String is a collection of alphabets,words or other characters.',
    'variable': 'A python variable is a symbolic name that is a reference or pointer to an object.',
    'list': 'Lists are used to store multiple items in a single variable.',
    'loop': 'Python for loops are used to loop through an iterable object(like a list,tuple,set,etc)and perform the same action for each entry .',
    'dictionary': "Dictionaries are used to store data values in key:value pairs.",
    'key': 'The first item in a key-value pair.',
    'value': 'An item associated with a key in a dictionary.',
    'comments': 'Comments in Python is the inclusion of short descriptions along with the code to increase its readability.',
    'float': 'Float is a method that returns a floating-point number for a provided number or string.',
    'boolean expression': 'The python boolean type is one of the built in data types. It is used to represent truth value of an expression.',
    }

for word, definition in glossary.items():
    print(f"\n{word.title()}: {definition}")

# Output –
String: String is a collection of alphabets,words or other characters.

Variable: A python variable is a symbolic name that is a reference or pointer to an object.

List: Lists are used to store multiple items in a single variable.

Loop: Python for loops are used to loop through an iterable object(like a list,tuple,set,etc)and perform the same action for each entry .

Dictionary: Dictionaries are used to store data values in key:value pairs.

Key: The first item in a key-value pair.

Value: An item associated with a key in a dictionary.

Comments: Comments in Python is the inclusion of short descriptions along with the code to increase its readability.

Float: Float is a method that returns a floating-point number for a provided number or string.

Boolean Expression: The python boolean type is one of the built in data types. It is used to represent truth value of an expression.

# Answer for Exercise 4 -

# Program –
rivers = {'Yangtze River': 'China','Danube River': 'Europe','Ganges River': 'India'}

for river, country in rivers.items():
    print(f"The {river.title()} flows through {country.title()}.")

print("\nThe following rivers are included in this data set:")
for river in rivers.keys():
    print(f"{river.title()}")

print("\nThe following countries are included in this data set:")
for country in rivers.values():
    print(f"{country.title()}")

# Output –   
The Yangtze River flows through China.
The Danube River flows through Europe.
The Ganges River flows through India.

The following rivers are included in this data set:
Yangtze River
Danube River
Ganges River

The following countries are included in this data set:
China
Europe
India 



