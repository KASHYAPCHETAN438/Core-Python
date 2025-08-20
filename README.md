# Python Basics

This repository contains beginner-friendly notes and examples for
learning Python programming. It covers the essential concepts like
variables, data types, operators, conditionals, loops, and functions
with clear explanations and code examples.

------------------------------------------------------------------------

## 📌 Introduction

-   **High-level Language** → Easy-to-read, powerful programming
    language used in web development, data science, AI, automation,
    etc.\
-   **Interpreted & Dynamically Typed** → No compilation required, no
    explicit type declaration.\
-   **Beginner-Friendly** → Syntax similar to English.

------------------------------------------------------------------------

## 🖨️ Input & Output

### `print()`

-   Purpose: Display output on the screen.\
-   **Arguments**:
    -   `objects` → values to print\
    -   `sep` → separator (default `" "`)\
    -   `end` → string added after output (default `" "`)

Example:

``` python
print("Hello", "World", sep="-", end="!!")
# Output: Hello-World!!
```

### `input()`

-   Purpose: Take user input (always as string).\
-   **Arguments**:
    -   `prompt` → message displayed before input

Example:

``` python
name = input("Enter your name: ")
print("Welcome,", name)
```

------------------------------------------------------------------------

## 📝 Variables

-   Containers for storing data.\
-   Python is **dynamically typed** → No need to declare types.

✅ Allowed: letters, digits (not at start), underscores\
❌ Not Allowed: start with digit, special symbols (@, #, ...), keywords

------------------------------------------------------------------------

## 🔢 Data Types

-   **Numeric** → `int`, `float`, `complex`\
-   **Sequence** → `str`, `list`, `tuple`, `range`\
-   **Set** → `set`, `frozenset`\
-   **Mapping** → `dict`\
-   **Boolean** → `True`, `False`\
-   **None** → `NoneType`\
-   **Binary** → `bytes`, `bytearray`, `memoryview`

------------------------------------------------------------------------

## 🧮 Operators

1.  Arithmetic → `+ - * / % // **`\
2.  Assignment → `= += -= *= /=`\
3.  Relational → `== != > < >= <=`\
4.  Logical → `and or not`\
5.  Bitwise → `& | ^ ~ << >>`\
6.  Identity → `is, is not`\
7.  Membership → `in, not in`

------------------------------------------------------------------------

## 🔀 Conditional Statements

-   **Simple if-else**\
-   **if-elif-else Ladder**\
-   **Nested if**\
-   **Ternary (Single-line if-else)**

Example:

``` python
marks = 78
if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
else:
    print("Fail")
```

------------------------------------------------------------------------

## 🔁 Loops

-   **For Loop** → Iterates over sequences or ranges\
-   **While Loop** → Repeats until a condition becomes False\
-   Supports **break** and **continue**

Example:

``` python
for i in range(5):
    print(i)

count = 1
while count <= 5:
    print(count)
    count += 1
```

------------------------------------------------------------------------

## ⚙️ Functions

-   **Built-in Functions** → e.g., `print()`, `len()`, `sum()`\
-   **User-defined Functions** → Created using `def`\
-   **Lambda Functions** → Anonymous, single-expression functions

Example:

``` python
def add(a, b):
    return a + b

square = lambda x: x**2
```

------------------------------------------------------------------------

## 📚 Key Takeaways

-   Python is simple, powerful, and beginner-friendly.\
-   Variables are dynamically typed.\
-   Rich set of **data types & operators**.\
-   Supports **control flow** with if-else, loops, and functions.\
-   Great for web, AI, automation, and more.
