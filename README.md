# 🐍 Python Learning Guide

A complete **Python fundamentals** and **Object-Oriented Programming (OOP)** guide — includes visuals, examples, and practice exercises for all levels.

---

## 📘 Table of Contents
1. [Installing Python](#installing-python)
2. [Variables](#variables)
3. [Data Types](#data-types)
4. [Operators](#operators)
5. [Mutability & Immutability](#mutability--immutability)
6. [Dictionaries](#dictionaries)
7. [Sets](#sets)
8. [Strings](#strings)
9. [Conditional Statements](#conditional-statements)
10. [Loops & Object-Oriented Programming (OOP)](#loops--object-oriented-programming-oop)

---

## 🧩 Installing Python
Download from the [official website](https://www.python.org/downloads/), install, and check version:
```bash
python --version
🧠 Variables
Variables are containers for data.
Example:

python
Copy code
age = 25
name = "Yonas"
✅ Allowed: letters, numbers, underscores
🚫 Not Allowed: start with numbers, special characters, or Python keywords

🧾 Data Types
Class	Description
Numeric	int, float, complex
String	str – sequence of characters
Sequence	list, tuple, range
Mapping	dict – key-value pairs
Boolean	True or False
Set	Unique unordered items

➗ Operators
Perform operations on values.

Arithmetic
+, -, *, /, //, %, **

Assignment
=, +=, -=, *=, /=

Comparison
==, !=, >, <, >=, <=

Logical
and, or, not

🔄 Mutability & Immutability
Type	Description	Examples
Mutable	Changeable	list, dict, set
Immutable	Fixed	int, float, str, tuple

🗝️ Dictionaries
Store data as key-value pairs:

python
Copy code
student = {"name": "Yonas", "age": 21}
Example Exercise:
Add new key/value, update, and display all items.

🍎 Sets
Unordered, unique collections:

python
Copy code
fruits = {"apple", "banana", "orange"}
fruits.add("mango")
✍️ Strings
Text enclosed in quotes:

python
Copy code
greeting = "Hello, Python!"
print(greeting.upper())
⚖️ Conditional Statements
python
Copy code
age = int(input("Enter age: "))
if age >= 18:
    print("You can vote.")
else:
    print("You are too young.")
🔁 Loops & Object-Oriented Programming (OOP)
🔂 Loops in Python
Used to repeat code efficiently.

For Loop

python
Copy code
for i in range(5):
    print(i)
While Loop

python
Copy code
x = 1
while x <= 5:
    print(x)
    x += 1
💡 Loop Exercise
Print pattern:

yaml
Copy code
1
12
123
1234
🧱 Object-Oriented Programming (OOP)
Organize code into classes and objects for reusability.

Example

python
Copy code
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    def display(self):
        print(f"Name: {self.name}, Age: {self.age}")

p1 = Person("Yonas", 21)
p1.display()
Core Concepts

Concept	Description
Class	Blueprint for objects
Object	Instance of a class
Inheritance	Child class uses parent features
Encapsulation	Hiding internal details
Polymorphism	Same method, different behavior

🎯 Summary
✅ Loops automate repetition
✅ OOP improves structure and reusability
✅ Practice each concept with small projects to master Python 🚀

🧾 Author
Yonas Leykun
📍 Ethiopia | 💻 Full-Stack Developer | 🎓 Information Systems Student
