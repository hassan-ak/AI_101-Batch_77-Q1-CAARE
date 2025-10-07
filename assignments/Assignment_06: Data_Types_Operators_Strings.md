# 📝 Assignment 06: Data Types, Operators & Strings

## 📌 Instructions

- Complete this assignment in **Google Colab**.
- Save your file with the name: **`YourPIAICRollNumber_Assignment04.ipynb`** (e.g., `PIAIC12345_Assignment02.ipynb`).
- After completing, **share the Colab link** (make sure the link is accessible).
- Attempt **all questions from Part A–F**.
- The **Bonus Challenge Section** is **optional** – attempt only if you want to explore further.

---

## Part A – Data Types & Type Casting

1. Create variables of the following data types and print their values and types:

   - Integer
   - Float
   - Complex number
   - Boolean
   - String
   - List
   - Tuple
   - Set
   - Dictionary

2. Write a program that demonstrates implicit type casting:

   - Add an integer and a float
   - Add an integer and a complex number
   - Print the results and their types

3. Create a program that demonstrates explicit type casting:

   - Convert a float to an integer (show truncation)
   - Convert a string `"123"` to an integer
   - Convert a string `"45.67"` to a float
   - Convert an integer to a string
   - Convert a boolean to an integer

4. Write a program that demonstrates the `isinstance()` function:

   - Check if a variable is an integer
   - Check if a variable is a float
   - Check if a variable is a string
   - Print the results

5. Demonstrate truthy and falsy values by testing the following with `bool()`:
   - `0`, `1`, `-10`
   - `""`, `"Hello"`
   - `[]`, `[1, 2, 3]`
   - `{}`, `{"name": "Ali"}`

---

## Part B – Numeric Types & Operations

6. Create a program that calculates the following for two numbers entered by the user:

   - Addition
   - Subtraction
   - Multiplication
   - Division (regular and floor)
   - Modulus
   - Exponentiation

7. Write a program that demonstrates the difference between `/` and `//`:

   - Divide 17 by 5 using both operators
   - Show the data type of each result

8. Create a complex number and demonstrate:

   - Accessing the real part using `.real`
   - Accessing the imaginary part using `.imag`
   - Adding two complex numbers

9. Write a program that uses the modulus operator to determine:

   - Whether a number is even or odd
   - The last digit of a number

10. Create a program that converts temperature from Celsius to Fahrenheit using the formula:
    - `F = (C * 9/5) + 32`

---

## Part C – Operators & Expressions

11. Demonstrate all comparison operators with examples:

    - `==`, `!=`, `>`, `<`, `>=`, `<=`
    - Use numbers and show the boolean results

12. Write a program using logical operators (`and`, `or`, `not`):

    - Check if a number is between 10 and 20
    - Check if a number is either less than 5 or greater than 15
    - Use `not` to reverse a boolean value

13. Create a program demonstrating assignment operators:

    - Start with `x = 10`
    - Use `+=`, `-=`, `*=`, `/=`, `//=`
    - Print the value after each operation

14. Write a program using the walrus operator (`:=`):

    - Ask for user input and assign it in an if statement
    - Example: `if (age := int(input("Enter age: "))) >= 18:`

15. Demonstrate identity operators (`is`, `is not`):

    - Create two lists with same values
    - Show the difference between `==` and `is`
    - Show `id()` of both lists

16. Write a program using membership operators (`in`, `not in`):

    - Check if a number exists in a list
    - Check if a letter exists in a string
    - Check if a key exists in a dictionary

17. Create a program demonstrating chained comparison operators:
    - Check if: `10 < x < 20`
    - Check if: `5 <= y <= 15`

---

## Part D – Strings & String Methods

18. Create a multi-line string using triple quotes and print it.

19. Demonstrate escape sequences:

    - Print a string with a tab (`\t`)
    - Print a string with a newline (`\n`)
    - Print a string with double quotes inside
    - Print a string with a backslash

20. Create a program that uses the following string methods:

    - `.upper()` - Convert to uppercase
    - `.lower()` - Convert to lowercase
    - `.title()` - Convert to title case
    - `.strip()` - Remove whitespace
    - `.replace()` - Replace a word

21. Write a program using string slicing:

    - Get the first 5 characters
    - Get the last 5 characters
    - Get characters from index 2 to 7
    - Reverse a string using slicing

22. Demonstrate string methods:

    - `.split()` - Split a sentence into words
    - `.join()` - Join a list of words with a separator
    - `.find()` - Find the position of a substring
    - `.count()` - Count occurrences of a character

23. Create a program using string formatting:

    - Use the `%` operator with `%s`, `%d`, `%f`
    - Use `.format()` method
    - Use f-strings

24. Write a program that compares two strings:

    - Use `==` to check equality
    - Use `>` and `<` to compare lexicographically
    - Compare "apple" and "banana"

25. Demonstrate string repetition:
    - Multiply a string by an integer
    - Create a pattern using string repetition (like a row of stars)

---

## Part E – Memory Management & Advanced Concepts

26. Write a program demonstrating integer interning:

    - Create two variables with value 100 (within -5 to 256)
    - Check if they share the same memory using `is`
    - Create two variables with value 1000 (outside interning range)
    - Check if they share the same memory

27. Demonstrate string interning and string pool:

    - Create two variables with the same short string
    - Check if they share memory using `id()`
    - Create two variables with the same long string (>20 chars)
    - Check if they share memory

28. Write a program using the `id()` function:

    - Create a variable
    - Print its id
    - Assign the variable to another variable
    - Print both ids and compare

29. Create a program demonstrating the None type:

    - Assign None to a variable
    - Check its type
    - Use None in a conditional statement
    - Show that None is a singleton (all None values share the same id)

30. Write a program using `isinstance()` to validate user input:
    - Ask for a number
    - Check if it's an integer or float
    - Handle string input appropriately

---

## Part F – Problem Solving & Logical Thinking

**Note:** These questions focus on building your problem-solving skills. Think through the logic before coding!

41. **Number Pattern Checker**

    - Ask the user for a number
    - Check if the number is:
      - Positive or negative
      - Even or odd
      - Divisible by both 3 and 5
    - Print a detailed message for each condition

42. **String Analyzer**

    - Ask the user to enter a sentence
    - Count and display:
      - Number of vowels (a, e, i, o, u)
      - Number of consonants
      - Number of spaces
      - Number of digits
    - Make it case-insensitive

43. **Simple Grade Calculator**

    - Ask for marks in 3 subjects
    - Calculate total and percentage
    - Assign grade based on percentage:
      - 90-100: A+
      - 80-89: A
      - 70-79: B
      - 60-69: C
      - Below 60: F
    - Display all information

44. **Password Strength Checker**

    - Ask user to create a password
    - Check if password has:
      - At least 8 characters
      - At least one uppercase letter
      - At least one lowercase letter
      - At least one digit
      - At least one special character (@, #, $, etc.)
    - Give feedback on what's missing

45. **Number Reverser**

    - Ask user for a number (e.g., 12345)
    - Reverse the number and display it (54321)
    - Do this using string operations AND mathematical operations
    - Show both methods

46. **Bill Calculator**

    - Ask for the bill amount
    - Ask for tip percentage (15%, 18%, 20%)
    - Calculate:
      - Tip amount
      - Total amount (bill + tip)
      - If splitting, ask number of people and show per-person amount

47. **Email Validator (Basic)**

    - Ask user for an email address
    - Check if it:
      - Contains exactly one '@' symbol
      - Has at least one '.' after the '@'
      - Doesn't start or end with special characters
    - Print "Valid" or "Invalid" with reasons

48. **Acronym Generator**

    - Ask for a phrase (e.g., "Application Programming Interface")
    - Generate and display the acronym (API)
    - Make all letters uppercase
    - Handle multiple spaces properly

49. **Number Guessing Checker**

    - Set a secret number in your code (e.g., 42)
    - Ask user to guess
    - Tell them if their guess is:
      - Too low
      - Too high
      - Correct
    - Also tell them the difference between their guess and the actual number

50. **Time Converter**

    - Ask for time in seconds
    - Convert and display in format: "X hours, Y minutes, Z seconds"
    - Example: 3665 seconds = "1 hour, 1 minute, 5 seconds"

51. **Leap Year Checker**

    - Ask for a year
    - Determine if it's a leap year using the rules:
      - Divisible by 4 BUT not by 100
      - OR divisible by 400
    - Explain why it is or isn't a leap year

52. **Phone Number Formatter**

    - Ask for a 10-digit phone number (without formatting)
    - Format it as: (XXX) XXX-XXXX
    - Validate that exactly 10 digits were entered
    - Handle spaces and dashes in input

53. **String Compressor**

    - Take a string like "aaabbbcc"
    - Compress it to "a3b3c2"
    - If compressed version is longer, return original

54. **BMI Calculator with Categories**

    - Ask for weight (kg) and height (meters)
    - Calculate BMI = weight / (height²)
    - Categorize:
      - Below 18.5: Underweight
      - 18.5-24.9: Normal
      - 25-29.9: Overweight
      - 30+: Obese
    - Display BMI and category

55. **Caesar Cipher (Basic)**

    - Ask for a word and a shift number
    - Shift each letter by that number in the alphabet
    - Example: "abc" with shift 1 becomes "bcd"
    - Handle only lowercase letters

56. **Shopping Discount Calculator**

    - Ask for original price
    - Ask for discount percentage
    - Calculate:
      - Discount amount
      - Final price
      - Amount saved
    - If final price > 1000, apply additional 5% discount

57. **Name Formatter**

    - Ask for full name (may have inconsistent spaces/caps)
    - Format properly: "First Last" with proper capitalization
    - Remove extra spaces
    - Example: " jOhN DOE " → "John Doe"

58. **Palindrome Number Checker**

    - Ask for a number
    - Check if it's a palindrome (reads same forwards/backwards)
    - Example: 121, 12321 are palindromes
    - 123 is not

59. **Character Frequency Counter**

    - Ask for a word or sentence
    - Display each unique character and how many times it appears
    - Ignore spaces
    - Show in alphabetical order

60. **Simple Interest vs Compound Interest**
    - Ask for: Principal amount, Rate, Time (years)
    - Calculate and display both:
      - Simple Interest: (P × R × T) / 100
      - Compound Interest: P × (1 + R/100)^T - P
    - Show the difference between them

---

## 🌟 Bonus Challenge Section (Optional)

31. Create a calculator that supports all arithmetic operations and uses the walrus operator for continuous operation until the user types "exit".

32. Write a program that demonstrates the difference between shallow copy and deep copy using lists.

33. Create a program that finds all occurrences of a substring in a string and prints their positions.

34. Write a program that converts a binary string (like "1010") to its decimal equivalent without using `int()` conversion.

35. Create a program that reverses the words in a sentence but keeps the sentence order the same:

    - Input: `"Hello World Python"`
    - Output: `"olleH dlroW nohtyP"`

36. Write a program using the `format()` function to align text:

    - Left align
    - Right align
    - Center align
    - Use width of 20 characters

37. Create a program that checks if a string is a palindrome (reads same forwards and backwards) ignoring spaces and case.

38. Write a program that demonstrates all bitwise operators:

    - AND (`&`)
    - OR (`|`)
    - XOR (`^`)
    - NOT (`~`)
    - Left shift (`<<`)
    - Right shift (`>>`)

39. Create a program that swaps two variables:

    - Using a temporary variable
    - Without using a temporary variable (Python way)
    - Using arithmetic operations

40. Write a comprehensive program that takes a paragraph of text and provides statistics:
    - Total number of characters
    - Total number of words
    - Total number of sentences
    - Most frequent character
    - Most frequent word
    - Average word length

---

## 💡 Learning Outcomes

After completing this assignment, you should be able to:

✅ Understand and work with all Python data types
✅ Perform type casting (implicit and explicit)
✅ Use all types of operators in Python
✅ Master string operations and methods
✅ Understand memory management concepts
✅ Work with the id() and isinstance() functions
✅ Apply string formatting techniques
✅ Understand integer and string interning
✅ **Break down problems into logical steps**
✅ **Apply computational thinking to real-world scenarios**
✅ **Combine multiple concepts to solve practical problems**
✅ **Debug and validate user input**
✅ **Think algorithmically and develop problem-solving strategies**

---

## 📚 Topics Covered

This assignment covers:

- **Lesson 02:** Data Types (Numeric, Boolean, Sequence, Set, Mapping, Binary, None)
- **Lesson 03:** Operators (Arithmetic, Comparison, Logical, Assignment, Identity, Membership)
- **Lesson 04:** Strings & Type Casting (String methods, formatting, comparison, interning)
- **Problem Solving:** Logical thinking, algorithm design, real-world applications

---

✅ **Reminder**: Submit your **Google Colab link** named with your **PIAIC Roll Number**.
✨ The Bonus Challenge Section is optional but highly recommended for mastery!

**Good luck! 🚀**
