[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285565&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

# Python Basics
Python is a high-level, interpreted programming language known for its readability and simplicity. Key features include:Easy-to-read syntax: Resembles English, making it accessible.
Dynamically typed: No need to declare variable types.
Extensive standard library: Rich set of modules and packages.
Interpreted language: Runs directly from the source code without a separate compilation step.
Community support: Large and active user community.
#Use Cases:Web Development: Frameworks like Django and Flask.
Data Analysis: Libraries like pandas, NumPy, and Matplotlib.
Machine Learning: Libraries like TensorFlow and scikit-learn.
Automation: Scripting and task automation.
#References:
Python Software Foundation. (n.d.). Python. Retrieved from https://www.python.org
VanderPlas, J. (2016). Python Data Science Handbook: Essential Tools for Working with Data. O'Reilly Media.

# PYTHON INSTALLATION 
#Windows:
Download Python from https://www.python.org.
Run the installer and check "Add Python to PATH".
Verify installation with python --version in Command Prompt.
Create a virtual environment: python -m venv myenv.

#References:
Python Software Foundation. (n.d.). Python Setup and Usage. Retrieved from https://docs.python.org/3/using/index.html

# Python Syntax and Semantics
print("Hello, World!")
print(): Function to output text to the console.
"Hello, World!": String literal enclosed in double quotes.
#References:
Python Software Foundation. (n.d.). The Python Standard Library: Built-in Functions. Retrieved from https://docs.python.org/3/library/functions.html#print

# DATA TYPES AND VARIABLES
Integers (int): Whole numbers.
Floating-point numbers (float): Decimal numbers.
Strings (str): Text data.
Booleans (bool): True/False values.
Lists (list): Ordered collections.
Dictionaries (dict): Key-value pairs.
#example
x = 10          # int
y = 3.14        # float
name = "Alice"  # str
is_student = True  # bool
numbers = [1, 2, 3]  # list
person = {"name": "Bob", "age": 25}  # dict

print(x, y, name, is_student, numbers, person)

#references
Python Software Foundation. (n.d.). Built-in Types. Retrieved from https://docs.python.org/3/library/stdtypes.html

# Control Structures
Conditional Statements: Used to execute code based on conditions.
Loops: Used to iterate over sequences.

#EXAMPLES
#if-else statement
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")

#for loop
for i in range(5):
    print(i)

#REFFERENCES
Python Software Foundation. (n.d.). Control Flow Tools. Retrieved from https://docs.python.org/3/tutorial/controlflow.html

# Functions in Python
Functions are reusable blocks of code that perform a specific task. They help organize code, reduce redundancy, and improve readability.

#EXAMPLES
def add(a, b):
    return a + b

#Call the function
result = add(5, 3)
print(result)

#REFERENCES
Python Software Foundation. (n.d.). Defining Functions. Retrieved from https://docs.python.org/3/tutorial/controlflow.html#defining-functions

# Lists and Dictionaries
Lists: Ordered, mutable collections of elements.
Dictionaries: Unordered collections of key-value pairs.
#example

# List example
numbers = [1, 2, 3, 4, 5]
numbers.append(6)
print(numbers)

# Dictionary example
person = {"name": "Alice", "age": 30}
person["city"] = "New York"
print(person)
#References:
Python Software Foundation. (n.d.). Data Structures. Retrieved from https://docs.python.org/3/tutorial/datastructures.html

# Exception Handling

Exception handling manages runtime errors, allowing the program to continue execution.

Example:
try:
    x = 1 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("This will always execute")
#References:
Python Software Foundation. (n.d.). Errors and Exceptions. Retrieved from https://docs.python.org/3/tutorial/errors.html
# Modules and Packages
Modules: Single files containing Python code.
Packages: Directories containing multiple modules.
ExAmples
import math
print(math.sqrt(16))
#REFERENCES

Python Software Foundation. (n.d.). Modules. Retrieved from https://docs.python.org/3/tutorial/modules.html

# File I/O

#read from file example
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
#Write to a file
lines = ["Hello, World!", "Python is great!"]
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')
#References:
Python Software Foundation. (n.d.). Reading and Writing Files. Retrieved from https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files
