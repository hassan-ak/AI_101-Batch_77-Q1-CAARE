# Class 07 - September 28th, 2025

## 📚 Today's Learning Summary

Here's a **comprehensive class-style summary with bullet notes** combining Python Crash Course chapters (4, 5, and 7) with Modern AI Python fundamentals from [Panaversity's Learn Modern AI Python](https://github.com/panaversity/learn-modern-ai-python) repository:

---

## 📊 Data Types & Memory Management

### Mutable vs Immutable Types

- **Mutable (Changeable)**: `list`, `dict`, `set`, `bytearray`
  - Can be modified after creation
  - Memory efficient (modify in place)
  - Not hashable (except `frozenset`)
- **Immutable (Unchangeable)**: `int`, `float`, `str`, `tuple`, `frozenset`, `bytes`
  - Cannot be changed after creation
  - Creates new objects when modified
  - Hashable (can be used as dictionary keys)

### Data Type Applications

- **Lists**: Dynamic arrays for storing collections
- **Tuples**: Immutable sequences for constant values
- **Dictionaries**: Key-value pairs for efficient lookups
- **Sets**: Unique elements with fast membership testing

---

## 🔧 Operators, Keywords & Variables

### Essential Operators

- **Arithmetic**: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- **Comparison**: `==`, `!=`, `<`, `>`, `<=`, `>=`
- **Logical**: `and`, `or`, `not`
- **Membership**: `in`, `not in`
- **Identity**: `is`, `is not`

### Variable Best Practices

- **Naming Conventions**: Use snake_case for variables and functions
- **Scope Management**: Understand local vs global scope
- **Memory Efficiency**: Choose appropriate data types

---

## 📘 Chapter 4 – Working with Lists

- **Looping**: Use `for` loops to iterate through entire lists and perform actions on each element.
- **Indentation**: Python uses indentation to structure code; errors occur if lines are misaligned.
- **Numerical lists**: Create number sequences with `range()`, calculate stats (min, max, sum).
- **List comprehensions**: Short, powerful way to build new lists from existing ones.
- **Slicing**: Extract parts of lists (`list[0:3]`), loop over slices, or copy lists with slicing.
- **Tuples**: Immutable sequences; useful when values must stay constant.
- **Code style (PEP 8)**: Use consistent indentation, keep lines under 80 chars, and structure code for readability.

---

## 📘 Chapter 5 – if Statements

- **Conditional tests**: Check for equality, inequality, greater/less comparisons, and membership in lists.
- **if statements**: Control flow using:

  - `if` (simple condition)
  - `if-else` (two outcomes)
  - `if-elif-else` (multiple conditions)

- **Multiple conditions**: Combine with `and`, `or`, or separate `if` blocks.
- **Booleans**: Expressions evaluate to `True` or `False` and guide logic.
- **Using with lists**: Check if items exist, handle empty lists, or work with multiple lists.
- **Styling**: Write clean, consistent conditionals for clarity.

---

## 📘 Chapter 7 – User Input and while Loops

- **input()**: Accepts user input as a string; use `int()` to convert to numbers.
- **Prompts**: Write clear instructions so users know what to enter.
- **Modulo operator (%)**: Useful for checking divisibility (e.g., even/odd checks).
- **while loops**: Repeat code until a condition becomes false.
- **Flags**: Use a variable to indicate whether a program should keep running.
- **break/continue**:

  - `break` → exit loop immediately.
  - `continue` → skip rest of loop and move to next iteration.

- **Loop control**: Avoid infinite loops by ensuring conditions eventually become false.

## 🔗 Additional Resources

### 📓 Class Materials

- [Today's Class Notebook](https://colab.research.google.com/drive/12ziZ7uoSov5YRT3sJGXa80rZIfjL1aR4?usp=sharing) - Google Colab notebook for Class 07

### 📚 Repository Links

- [Learn Modern AI Python Repository](https://github.com/panaversity/learn-modern-ai-python)
- [Python Basics](https://github.com/panaversity/learn-modern-ai-python/tree/main/00_python_colab/-01_basics)
- [Introduction to Python](https://github.com/panaversity/learn-modern-ai-python/tree/main/00_python_colab/01_introduction_to_python)
- [Data Types](https://github.com/panaversity/learn-modern-ai-python/tree/main/00_python_colab/02_data_types)
- [Operators, Keywords & Variables](https://github.com/panaversity/learn-modern-ai-python/tree/main/00_python_colab/03_operators_keywords_variables)

---

_Class conducted on September 28th, 2025 - AI-101 Batch 77 Q1 CAARE_
