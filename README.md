
# 🐍 Python Basics & OOP Concepts

This repository contains beginner-friendly notes and examples for learning Python programming. It covers core Python concepts, data types, control flow, functions, and OOP (Object-Oriented Programming) concepts with clear explanations and examples.

## 📌 Introduction

Python is a **high-level language**, which is easy to read and powerful. It is widely used in **web development, data science, AI, automation**, and more. Python is **interpreted** and **dynamically typed**, meaning no compilation is required and no explicit type declaration is needed. Python is beginner-friendly with syntax similar to English and runs on multiple platforms such as Windows, Linux, and macOS.

## 🖨️ Input & Output

Python uses the `print()` function to display output on the screen. You can provide multiple objects separated by commas and use `sep` to define a separator and `end` to define what comes at the end of output. Example:  
```python
print("Hello", "World", sep="-", end="!!")
# Output: Hello-World!!

To take input from the user, Python uses the input() function, which always returns a string. You can provide a prompt to show before input. Example:

name = input("Enter your name: ")
print("Welcome,", name)

## 📝 Variables

Variables are containers to store data. Python is dynamically typed, so you don't need to declare the type. Allowed variable names can include letters, digits (not at start), and underscores. They cannot start with a digit or contain special symbols like @, # or keywords.

## 🔢 Data Types

Python has several data types:

Numeric → int, float, complex

Sequence → str, list, tuple, range

Set → set, frozenset

Mapping → dict

Boolean → True, False

None → NoneType

Binary → bytes, bytearray, memoryview

## 🧮 Operators

Python supports multiple types of operators:

Arithmetic → + - * / % // **

Assignment → = += -= *= /=

Relational → == != > < >= <=

Logical → and or not

Bitwise → & | ^ ~ << >>

Identity → is, is not

Membership → in, not in

🔀 Conditional Statements

Python supports if-else, if-elif-else, nested if, and ternary operations. Example:

marks = 78
if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
else:
    print("Fail")

## 🔁 Loops

Python supports for and while loops. Example:

# For Loop
for i in range(5):
    print(i)

# While Loop
count = 1
while count <= 5:
    print(count)
    count += 1


You can use break to exit a loop early and continue to skip the current iteration.

## ⚙️ Functions

Functions in Python can be built-in, user-defined, or lambda (anonymous). They can also use default arguments, *args, and **kwargs. Example:

def add(a, b=0):
    return a + b

def multiply(*nums):
    result = 1
    for n in nums:
        result *= n
    return result

square = lambda x: x**2

------
## 📦 Core Python Concepts

Strings:

s = "Hello World"
print(s.upper())  # HELLO WORLD
print(s.split())  # ['Hello', 'World']


Lists:

lst = [1, 2, 3]
lst.append(4)
print(lst)  # [1, 2, 3, 4]


Tuples:

t = (1, 2, 3)
print(t[0])  # 1


Sets:

s = {1, 2, 2, 3}
print(s)  # {1, 2, 3}


Dictionaries:

d = {"name": "Mohit", "age": 22}
print(d["name"])  # Mohit


Type Conversion:

x = int("10")
y = str(20)
z = float(3)


## Exception Handling:

try:
    num = int(input("Enter a number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero")
except ValueError:
    print("Invalid input")
finally:
    print("Execution complete")
-----

## 🏗️ OOP Concepts in Python

Classes & Objects:

class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary

    def display(self):
        print(f"{self.name} earns {self.salary}")

emp = Employee("Mohit", 50000)
emp.display()


Inheritance:

class Person:
    def __init__(self, name):
        self.name = name

class Student(Person):
    def __init__(self, name, roll):
        super().__init__(name)
        self.roll = roll


Polymorphism:

print(len("Hello"))  # 5
print(len([1,2,3]))  # 3


Encapsulation & Data Hiding:

class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.__salary = salary

    def get_salary(self):
        return self.__salary


Abstraction:

class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.__salary = salary

    @property
    def salary(self):
        return self.__salary

    @salary.setter
    def salary(self, value):
        if value > 0:
            self.__salary = value


Special Methods (Magic Methods):

class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary

    def __str__(self):
        return f"{self.name} earns {self.salary}"

emp = Employee("Mohit", 50000)
print(emp)

📚 Key Takeaways

Python is simple, powerful, and beginner-friendly

Dynamically typed, interpreted language

Supports all core programming constructs: variables, loops, conditionals, functions

Rich OOP features: Classes, Objects, Inheritance, Polymorphism, Encapsulation, Abstraction

Widely used in web development, data science, AI, automation, and more


update this readme file and give me attractive readme file 
### BLACKBOX.AI

# 🐍 Python Basics & OOP Concepts

[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=yellow)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/yourusername/python-basics-oop?style=social)](https://github.com/yourusername/python-basics-oop)

Welcome to **Python Basics & OOP Concepts**! This beginner-friendly repository is your go-to guide for mastering the fundamentals of Python programming. Whether you're new to coding or brushing up on essentials, you'll find clear explanations, hands-on examples, and practical code snippets. Python is a versatile, high-level language loved for its simplicity and power—perfect for web development, data science, AI, automation, and more.

Python is **interpreted** (no compilation needed) and **dynamically typed** (no explicit type declarations), making it easy to learn and run on Windows, Linux, macOS, and beyond. Let's dive in!

## 📋 Table of Contents

- [Installation & Setup](#-installation--setup)
- [Input & Output](#-input--output)
- [Variables](#-variables)
- [Data Types](#-data-types)
- [Operators](#-operators)
- [Conditional Statements](#-conditional-statements)
- [Loops](#-loops)
- [Functions](#-functions)
- [Core Python Concepts](#-core-python-concepts)
- [Exception Handling](#-exception-handling)
- [OOP Concepts](#-oop-concepts)
- [Key Takeaways](#-key-takeaways)
- [Contributing](#-contributing)
- [License](#-license)

## 🚀 Installation & Setup

1. **Install Python**: Download the latest version (3.8+) from [python.org](https://www.python.org/downloads/). Verify installation:
   ```bash
   python --version
   ```

2. **Run Examples**: Save code snippets into `.py` files and execute:
   ```bash
   python filename.py
   ```

3. **IDE Recommendation**: Use VS Code, PyCharm, or Jupyter Notebook for an interactive experience.

No additional libraries needed for these basics—everything runs with vanilla Python!

## 🖨️ Input & Output

Output text or variables using `print()`. Customize with `sep` (separator) and `end` (ending character).

```python
print("Hello", "World", sep="-", end="!!\n")
# Output: Hello-World!!
```

Input from users via `input()`, which always returns a string. Add a prompt for clarity:

```python
name = input("Enter your name: ")
print(f"Welcome, {name}!")
# Example Input: Alice
# Output: Welcome, Alice!
```

## 📝 Variables

Variables store data without needing type declarations (thanks to dynamic typing). Rules:
- Start with a letter or underscore (`_`).
- Can include letters, digits, and underscores.
- Case-sensitive; avoid Python keywords (e.g., `if`, `for`).

```python
name = "Alice"  # String
age = 25        # Integer
height = 5.6    # Float
is_student = True  # Boolean
```

## 🔢 Data Types

Python's built-in types are categorized as follows:

| Category   | Types                  | Description                          | Example                  |
|------------|------------------------|--------------------------------------|--------------------------|
| **Numeric** | `int`, `float`, `complex` | Whole numbers, decimals, imaginary | `42`, `3.14`, `1+2j`    |
| **Sequence** | `str`, `list`, `tuple`, `range` | Ordered collections | `"Hello"`, `[1,2]`, `(1,2)`, `range(5)` |
| **Set**    | `set`, `frozenset`    | Unordered, unique elements          | `{1,2}`, `frozenset([1,2])` |
| **Mapping** | `dict`                | Key-value pairs                     | `{"key": "value"}`      |
| **Boolean** | `bool`                | True/False values                   | `True`, `False`         |
| **None**   | `NoneType`            | Represents absence of value         | `None`                  |
| **Binary** | `bytes`, `bytearray`, `memoryview` | Immutable/mutable byte sequences | `b'hello'`, `bytearray(b'hi')` |

Use `type()` to check: `type(42)` returns `<class 'int'>`.

## 🧮 Operators

Python offers a rich set for computations and logic:

- **Arithmetic**: `+`, `-`, `*`, `/`, `%` (modulo), `//` (floor division), `**` (exponent).
- **Assignment**: `=`, `+=`, `-=`, `*=`, `/=`.
- **Relational**: `==`, `!=`, `>`, `<`, `>=`, `<=`.
- **Logical**: `and`, `or`, `not`.
- **Bitwise**: `&` (AND), `|` (OR), `^` (XOR), `~` (NOT), `<<` (left shift), `>>` (right shift).
- **Identity**: `is`, `is not` (checks object identity).
- **Membership**: `in`, `not in` (checks presence in sequences/sets).

Example:
```python
x, y = 10, 3
print(x + y)    # 13
print(x // y)   # 3 (floor division)
print(x > y)    # True
```

## 🔀 Conditional Statements

Control flow with `if`, `elif`, `else`, nested conditions, or ternary operators.

```python
marks = 78
if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
else:
    print("Fail")
# Output: Grade B

# Ternary Example
status = "Pass" if marks >= 50 else "Fail"
print(status)  # Pass
```

## 🔁 Loops

Iterate with `for` (over sequences) or `while` (condition-based). Use `break` to exit early, `continue` to skip iterations.

```python
# For Loop
for i in range(5):  # 0 to 4
    print(i)
# Output: 0 1 2 3 4

# While Loop
count = 1
while count <= 5:
    print(count)
    count += 1
# Output: 1 2 3 4 5
```

## ⚙️ Functions

Reusable code blocks: built-in (e.g., `len()`), user-defined, or lambda (anonymous). Support default args, `*args` (variable positional), `**kwargs` (variable keyword).

```python
def add(a, b=0):  # Default arg
    return a + b

def multiply(*nums):  # Variable args
    result = 1
    for n in nums:
        result *= n
    return result

square = lambda x: x**2  # Lambda

print(add(5))         # 5
print(multiply(2, 3, 4))  # 24
print(square(3))      # 9
```

## 📦 Core Python Concepts

### Strings
Immutable sequences of characters. Methods: `upper()`, `split()`, etc.

```python
s = "Hello World"
print(s.upper())  # HELLO WORLD
print(s.split())  # ['Hello', 'World']
```

### Lists
Mutable, ordered collections. Methods: `append()`, `remove()`, etc.

```python
lst = [1, 2, 3]
lst.append(4)
print(lst)  # [1, 2, 3, 4]
```

### Tuples
Immutable, ordered collections.

```python
t = (1, 2, 3)
print(t[0])  # 1
```

### Sets
Unordered, unique elements. Auto-removes duplicates.

```python
s = {1, 2, 2, 3}
print(s)  # {1, 2, 3}
```

### Dictionaries
Mutable key-value pairs.

```python
d = {"name": "Mohit", "age": 22}
print(d["name"])  # Mohit
```

### Type Conversion
Cast between types:

```python
x = int("10")     # 10
y = str(20)       # '20'
z = float(3)      # 3.0
```

## ⚠️ Exception Handling

Handle errors gracefully with `try`, `except`, `else`, `finally`.

```python
try:
    num = int(input("Enter a number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero!")
except ValueError:
    print("Invalid input!")
finally:
    print("Execution complete.")
```

## 🏗️ OOP Concepts

Object-Oriented Programming in Python emphasizes classes, objects, and principles like inheritance and polymorphism.

### Classes & Objects
Blueprints for objects with attributes and methods.

```python
class Employee:
    def __init__(self, name, salary):  # Constructor
        self.name = name
        self.salary = salary

    def display(self):
        print(f"{self.name} earns ${self.salary}")

emp = Employee("Mohit", 50000)  # Object
emp.display()  # Mohit earns $50000
```

### Inheritance
Child classes inherit from parents using `super()`.

```python
class Person:
    def __init__(self, name):
        self.name = name

class Student(Person):
    def __init__(self, name, roll):
        super().__init__(name)
        self.roll = roll

student = Student("Alice", 101)
print(student.name)  # Alice
```

### Polymorphism
Same method name behaves differently (e.g., method overriding or built-in functions).

```python
print(len("Hello"))   # 5 (string length)
print(len([1, 2, 3])) # 3 (list length)
```

### Encapsulation & Data Hiding
Private attributes (prefixed with `__`) and getters/setters.

```python
class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.__salary = salary  # Private

    def get_salary(self):
        return self.__salary
```

### Abstraction
Hide implementation details using properties or abstract classes (from `abc` module).

```python
class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.__salary = salary

    @property
    def salary(self):  # Getter
        return self.__salary

    @salary.setter
    def salary(self, value):  # Setter with validation
        if value > 0:
            self.__salary = value

emp = Employee("Bob", 60000)
print(emp.salary)  # 60000
emp.salary = 70000  # Valid update
```

### Special Methods (Magic/Dunder Methods)
Customize object behavior, e.g., `__str__` for string representation.

```python
class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary

    def __str__(self):
        return f"{self.name} earns ${self.salary}"

emp = Employee("Mohit", 50000)
print(emp)  # Mohit earns $50000
```

## 📚 Key Takeaways

- Python is **simple, readable, and powerful**—ideal for beginners and pros.
- **Dynamically typed and interpreted**: Focus on logic, not boilerplate.
- Supports all essentials: variables, control flow, functions, and advanced OOP (classes, inheritance, polymorphism, encapsulation, abstraction).
- Versatile applications: From scripting to AI/ML.
- Practice by running these examples—experimentation is key!

Explore more with Python's official docs: [docs.python.org](https://docs.python.org/3/).


---

⭐ **Star this repo if it helped you!** Questions? Open an issue or reach out. Happy coding! 🚀
