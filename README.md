## PYTHON
# # INTRODUCTION
# 1.The Language



Python is one of the world's easiest and most popular programming languages.

# challenge icon
# Challenge(beginner)

Welcome to your first Python program! The code is already written for you.

# What to do:

1. Look at the code: print("Hello Python!")
2. Press the "Run Code" button to execute it
3. You should see "Hello Python!" appear in the output

# 2. Hello World!



The "Hello World!" is a simple program that outputs Hello World! to the screen.

In Python, we use print() to show words on the screen. The words go inside quotation marks.

Let's take a look at the "Hello World!" program in Python:

print("Hello World!")

# 3. Comments



Comments are notes you write inside your code. Python completely ignores them - they exist only to help humans understand the code.

To write a single-line comment, use the # symbol. Everything after # on that line is ignored:

#This is a comment

print("Hello!")

A comment can also be written at the end of a line, after the code:

print("Hello!")  # This prints Hello!

For comments that span several lines, use triple quotes (""") before and after the text:

"""
This is a multi-line comment.

Python ignores all of it.
"""
print("Welcome!")

Comments can also temporarily disable a line of code without deleting it:

#print("This line will NOT run")

print("This line will run")

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cc9613ae-dc7c-4e65-a376-a11a5a39ee43" />

# # VARIABLES
# 1. Numbers



Variables are containers that hold data values. They are used to store, manipulate, and display information within a program.

In short, a variable is like a memory unit that we can access by typing the name of the variable. 

Each variable has a unique name and a value that can be of different types. Python is capable of automatically detecting the variable type, which makes coding more efficient.

To initialize a variable, we use the following format:

variable_name = value
Let's take a look at the different types of numbers:

int - an integer, such as 1 or -2.

float - real number, such as 1.32 or 0.98.

For example:

To initialize a variable of type int with the name a and the value 3:

a = 3

To initialize a variable of type float with the name b and the value 13.2:

b = 13.2

Note: Variable names cannot start with a number. Use underscores to separate words (e.g., player_name), not spaces or hyphens..

# 2. String



A character is a single letter, digit, or symbol (for example: 1, 6, %, b, p, ., T, etc.). Python has no separate char type: a single character is simply a string of length 1.

The str (string) type is a sequence of one or more characters.

To initialize a string value in a variable, enclose it within single or double quotation marks:

s1 = 'This is a string'

s2 = "This is also a string"

In the above example, two string variables are initialized, named s1 and s2.

# 3. Boolean



A bool (Boolean) type has only 2 possible values: True or False.

Note that these values are case-sensitive, meaning they must start with a capital letter.

Here is an example of assigning a bool value to a variable:

variable_true = True

variable_false = False

In the above, two variables named variable_true and variable_false are initialized, with the values True and False respectively.

Booleans are the building blocks for creating logic in the programs we write. We have a whole chapter about logic and conditions.

# 4. Naming Conventions



Naming conventions are a set of guidelines that developers follow to make their code more readable and maintainable. Different programming languages often have different naming conventions. In python, variables are written in snake case - words are separated by underscores.

When writing a variable name be descriptive and use meaningful words

For example 

#Bad Naming

isActive = False  # not snake case

a = 10

b = "Hello"

x = True

#Good Naming

age = 10

greeting = "Hello"

is_active = True

# 5. Empty Variables



In Python, None is a special value that represents "nothing" or "no value." It's like an empty box - it exists, but there's nothing inside it. For example:

empty_box = None

In a real scenario you could use None to indicate that something was not initialized yet.

For example:

score = None  # Score hasn't been calculated yet


name = None   # Name hasn't been entered yet 

Note: None is not the same as 0, an empty string "", or False. Those are actual values: zero, empty text, and false. None means there is no value at all. The absence of a value is not an error; it simply means nothing has been assigned yet.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6a51a8b9-bd39-4003-b194-44ce77a9caf1" />

# OPERATORS PART 1

# 1. Arithmetic Operators



Operators are used to perform operations on values. 

First we will discuss the most basic arithmetic operators, they may be familiar from math classes.

Operator	Operation	Example
+	Addition	3 + 2 = 5
-	Subtraction	3 - 2 = 1
*	Multiplication	3 * 2 = 6
/	Division	4 / 2 = 2.0

Let's see a usage example.

a = 3
b = 5
c = a + b # c holds 8


When one expression contains several operators, Python follows the order used in maths: multiplication and division are calculated before addition and subtraction, and anything inside parentheses is calculated first.

z = 7 + 3 * 2   # z holds 13, because 3 * 2 is calculated first

z = (7 + 3) * 2 # z holds 20

# 2. Modulo Operator



The modulo operator % tells you what's left over after dividing one number by another.

result = dividend % divisor
dividend: The number being divided.
divisor: The number that divides the dividend.
result: The remainder of the division.

For example

result = 10 % 3

Here, 10 is divided by 3. 3 goes into 10 three times, with a remainder of 1. So, result will be 1.

Usually modulo is used for checking if a number is even or odd:

If a number is even, dividing it by 2 will leave a remainder of 0.

If a number is odd, dividing it by 2 will leave a remainder of 1.

To check this in code, we use the == operator, which checks if two values are equal to each other. For example, result == 0 asks "is result equal to 0?"

Special Case: When the dividend is smaller than the divisor, the result is simply the dividend itself.

For example:

5 % 8 = 5

Why? Since 8 cannot fit into 5 even once, the entire 5 remains as the remainder.

# 3.Arithmetic Shortcuts



Python created a cool shortcut for self-arithmetic operations.

For example, instead of writing:

a = 5
a = a + 3 # a holds 8
We can simplify it by writing +=:

a = 5
a += 3 # a holds 8
The += operator adds the value 3 to a.

This operation is valid for all arithmetic operations:

Operator	Shortcut
+	+=
-	-=
*	*=
  
 /	/=
 
 %	%=

 # CHALLENGE
 <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1c49dbda-111d-40d6-8d57-7dac7ef37a62" />

# 4.Comparison Operators



Comparison operators are used to compare between two operands.

Sometimes we need to check whether an operand is greater than, less than, or equal to another operand. The following table shows possible operators for comparison:

<img width="311" height="151" alt="image" src="https://github.com/user-attachments/assets/95555072-6147-40cb-8f2c-6e6f61b8d208" />


The comparison operator returns True if the comparison is true and False otherwise.

For example:

var1 = 13

var2 = 12

var3 = var1 != var2

var3 will hold True because var1 and var2 are not equal

Another example:

var1 = 13

var2 = 13

var3 = var1 == var2

var3 will hold True because var1 and var2 are equal

Remember the boolean type,  var3 is a boolean.


