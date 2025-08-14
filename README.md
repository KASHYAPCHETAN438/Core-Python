
# Python Basics

A beginner-friendly guide to learning the fundamentals of Python programming.  
This document covers essential Python concepts such as variables, data types, operators, conditionals, loops, functions, and more.

---

## 📌 Topics Covered

### 1. Variables
- Variables store data values in memory.
- Python is **dynamically typed** (no need to declare types explicitly).
- Naming rules:
  - Allowed: letters (A-Z, a-z), digits (0-9, but not at the start), underscores (`_`)
  - Not Allowed: starting with digits, special symbols (`@`, `#`, `$`, etc.), Python keywords (`if`, `for`, `class`, etc.)

### 2. Data Types
- **Numeric**: `int`, `float`, `complex`
- **Sequence**: `str`, `list`, `tuple`, `range`
- **Set**: `set`, `frozenset`
- **Mapping**: `dict`
- **Boolean**: `bool` (`True` / `False`)
- **NoneType**: `None`
- **Binary**: `bytes`, `bytearray`, `memoryview`

### 3. Operators
- **Arithmetic** → `+`, `-`, `*`, `/`, `%`, `//`, `**`
- **Assignment** → `=`, `+=`, `-=`, `*=`, `/=`, `%=` 
- **Comparison** → `==`, `!=`, `>`, `<`, `>=`, `<=`
- **Logical** → `and`, `or`, `not`
- **Bitwise** → `&`, `|`, `^`, `~`, `<<`, `>>`
- **Identity** → `is`, `is not`
- **Membership** → `in`, `not in`

### 4. Conditional Statements
- `if`, `if-else`, `if-elif-else`
- Nested `if`
- Ternary operator (single-line `if-else`)

### 5. Loops
- **For loop**
  - Iterates over sequences (lists, strings, ranges)
  - Supports `break` and `continue`
- **While loop**
  - Runs until a condition becomes false
  - Can create infinite loops if the condition never changes

### 6. Functions
- **Built-in Functions**: `print()`, `len()`, `sum()`, etc.
- **User-defined Functions**: Created with `def`
- **Lambda Functions**: One-line anonymous functions (`lambda args: expression`)

### 7. String Formatting
- **Old Style**: `%` operator
- **`str.format()`** method
- **F-strings** (Python 3.6+)

---

## 📂 Example Code

```python
# Variable and Type
x = 5
print(x, type(x))

# List
my_list = [1, 2, 3]
print(my_list)

# If-else
age = 20
print("Adult" if age >= 18 else "Minor")

# For loop
for i in range(3):
    print(i)

# Function
def greet(name):
    return f"Hello, {name}!"
print(greet("Chetan"))

