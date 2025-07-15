> 🧪 **Note:** This README-style document is designed to help candidates prepare and pass the technical entrance tests of YouCode.

# 📘 C Programming Exercises - From Beginner to Advanced

This document contains **10 categorized exercises** for each major concept in beginner-level C programming, followed by **10 mixed exercises** combining all those topics, and **10 advanced exercises** for the most challenging problems.

---

## 🔹 1. Variables (10 Exercises)

1. Declare an integer variable and print its value.
- **Input:** *None*
- **Output:** `The value of a is 10`

2. Store your age in a variable and print it.
    **Input:** *None*
    **Output:** `I am 22 years old.`

3. Swap the values of two variables.
    **Input:** `a = 5, b = 10`
    **Output:** `a = 10, b = 5`

4. Calculate the area of a rectangle using width and height variables.
    **Input:** `width = 4, height = 6`
    **Output:** `Area = 24`

5. Declare a `char` variable and print it.
    **Input:** `letter = 'A'`
    **Output:** `Character is A`

6. Create a float variable and assign a decimal value.
    **Input:** `price = 10.5`
    **Output:** `Price is 10.50`

7. Assign values to three variables and print their sum.
   **Input:** `a = 2, b = 3, c = 5`
   **Output:** `Sum = 10`

8. Modify a variable using another variable's value.
   **Input:** `a = 4, b = a * 2`
   **Output:** `b = 8`

9. Declare a constant using `#define` and print it.
   **Input:** `#define PI 3.14`
   **Output:** `PI = 3.14`

10. Create variables of all 4 main types and print them.
    **Input:** `int=1, float=1.5, char='C', double=3.14159`
    **Output:** `int: 1, float: 1.5, char: C, double: 3.141590`

---

## 🔹 2. Data Types (10 Exercises)

1. Print the size of each data type using `sizeof()`.
   **Output:** `int: 4 bytes, float: 4 bytes, double: 8 bytes...`

2. Declare and assign values to different types.
   **Input:** `int=5, float=1.1, char='z'...`
   **Output:** `Values printed`

3. Convert an `int` to a `float` and print.
   **Input:** `int=5`
   **Output:** `float=5.000000`

4. Use a `char` variable to store a symbol and print it.
   **Input:** `char='$'`
   **Output:** `Symbol: $`

5. Use a `float` variable and print it with 2 decimal places.
   **Input:** `float=3.1459`
   **Output:** `3.15`

6. Type casting from `float` to `int`.
   **Input:** `float=5.9`
   **Output:** `int=5`

7. Overflow demo with `char`.
   **Input:** `char=300`
   **Output:** *unexpected value (e.g., -56 depending on system)*

8. Print ASCII value of a character.
   **Input:** `char='A'`
   **Output:** `65`

9. Add an `int` and a `float`, store in `double`.
   **Input:** `int=3, float=2.5`
   **Output:** `Result=5.5`

10. Display limits using `limits.h`.
    **Output:** `INT_MAX = 2147483647...`

---

## 🔹 3. Conditions (if/else) (10 Exercises)

1. Check if a number is positive or negative.
   **Input:** `n = -3`
   **Output:** `Negative`

2. Check even or odd.
   **Input:** `n = 4`
   **Output:** `Even`

3. Compare two numbers.
   **Input:** `a = 5, b = 2`
   **Output:** `a is greater`

4. Maximum of 3 numbers.
   **Input:** `3, 9, 7`
   **Output:** `Max = 9`

5. Vowel or consonant.
   **Input:** `ch = 'e'`
   **Output:** `Vowel`

6. Divisible by 5 and 3.
   **Input:** `n = 15`
   **Output:** `Yes`

7. Age group.
   **Input:** `age = 16`
   **Output:** `Teenager`

8. Leap year.
   **Input:** `2024`
   **Output:** `Leap year`

9. Score to grade.
   **Input:** `score = 78`
   **Output:** `Grade = B`

10. Login check.
    **Input:** `username: admin, password: 1234`
    **Output:** `Access granted`

---

## 🔹 4. Operators (10 Exercises)

1. Add/subtract/multiply/divide two numbers.
   **Input:** `a=5, b=2`
   **Output:** `Sum=7, Diff=3, Mul=10, Div=2`

2. Modulo operation.
   **Input:** `7 % 3`
   **Output:** `1`

3. Logical AND.
   **Input:** `n = 7`
   **Output:** `Yes (between 5 and 10)`

4. Logical OR.
   **Input:** `n = 105`
   **Output:** `True`

5. NOT example.
   **Input:** `flag = 0`
   **Output:** `flag is false`

6. Increment/decrement.
   **Input:** `n = 5`
   **Output:** `++n = 6, --n = 4`

7. Compound assignment.
   **Input:** `x = 10, x += 5`
   **Output:** `x = 15`

8. Relational operators.
   **Input:** `a = 3, b = 7`
   **Output:** `a < b, a != b, etc.`

9. Basic calculator.
   **Input:** `a = 3, b = 2, op = +`
   **Output:** `5`

10. Divisible by both 3 and 7.
    **Input:** `n = 21`
    **Output:** `Yes`

---

## 🔹 5. Switch (10 Exercises)

1. Weekday name from number.
   **Input:** `3`
   **Output:** `Wednesday`

2. Calculator using switch.
   **Input:** `a=4, b=2, op='*'`
   **Output:** `8`

3. Grade to message.
   **Input:** `grade = 'A'`
   **Output:** `Excellent`

4. Month to season.
   **Input:** `month = 12`
   **Output:** `Winter`

5. Vowel/consonant with switch.
   **Input:** `ch='i'`
   **Output:** `Vowel`

6. Operation menu.
   **Input:** `2`
   **Output:** `Subtraction selected`

7. Weekday/weekend.
   **Input:** `7`
   **Output:** `Weekend`

8. Loop + switch menu.
   **Input:** `menu 1, 2, 3...`
   **Output:** `until user exits`

9. Use of default case.
   **Input:** `invalid = 10`
   **Output:** `Invalid choice`

10. Nested switch.
    **Input:** `Device: 1, Option: 2`
    **Output:** `Submenu Option 2`

---

## 🔹 6. Loops (10 Exercises)

1. Print 1 to 10.
   **Output:** `1 2 3 4 5 6 7 8 9 10`

2. Even numbers 1-100.
   **Output:** `2 4 6 ... 100`

3. Sum first 50 numbers.
   **Output:** `1275`

4. Factorial.
   **Input:** `5`
   **Output:** `120`

5. Multiplication table.
   **Input:** `3`
   **Output:** `3 x 1 = 3 ... 3 x 10 = 30`

6. Reverse digits.
   **Input:** `123`
   **Output:** `321`

7. Count digits.
   **Input:** `4567`
   **Output:** `4 digits`

8. Fibonacci series.
   **Input:** `n = 6`
   **Output:** `0 1 1 2 3 5`

9. do...while password check.
   **Input:** `wrong, wrong, correct`
   **Output:** `Access granted`

10. Prime number check.
    **Input:** `7`
    **Output:** `Prime`

---

## 🔁 7. Mixed Practice (10 Exercises)

1. Palindrome number.
   **Input:** `121`
   **Output:** `Palindrome`

2. Swap then calculate.
   **Input:** `a=5, b=3, op='+'`
   **Output:** `a=3, b=5, Sum=8`

3. Print vowels in string.
   **Input:** `"hello"`
   **Output:** `e o`

4. Even numbers divisible by 3.
   **Input:** `range 1–30`
   **Output:** `6 12 18 24 30`

5. Menu with loop.
   **Input:** `1 2 3 0`
   **Output:** `Add, Subtract, Multiply, Exit`

6. Age category.
   **Input:** `age = 45`
   **Output:** `Adult`

7. Looping calculator.
   **Input:** `a=2, b=3, op='*', repeat=yes`
   **Output:** `6`

8. Reverse string and check palindrome.
   **Input:** `"madam"`
   **Output:** `Palindrome`

9. Largest digit in number.
   **Input:** `5489`
   **Output:** `9`

10. Login with retry limit.
    **Input:** `3 wrong attempts`
    **Output:** `Access denied after 3 tries`

---

## 🔥 8. Advanced Challenges (10 Exercises)

1. **Complete Multiplication Table Generator**
   Create a program that generates multiplication tables for any range.
   **Input:** `start=3, end=5, max=12`
   **Output:** 
   ```
   Table for 3:
   3 x 1 = 3   3 x 2 = 6   3 x 3 = 9   3 x 4 = 12
   3 x 5 = 15  3 x 6 = 18  3 x 7 = 21  3 x 8 = 24
   3 x 9 = 27  3 x 10 = 30 3 x 11 = 33 3 x 12 = 36
   
   Table for 4:
   4 x 1 = 4   4 x 2 = 8   4 x 3 = 12  4 x 4 = 16
   ...
   ```

2. **Number Pattern Diamond**
   Create a diamond pattern with numbers.
   **Input:** `n = 5`
   **Output:**
   ```
       1
      123
     12345
    1234567
   123456789
    1234567
     12345
      123
       1
   ```

3. **Prime Number Sieve**
   Generate all prime numbers up to N using optimized algorithm.
   **Input:** `n = 30`
   **Output:** `2 3 5 7 11 13 17 19 23 29`

4. **Advanced Calculator with Memory**
   Calculator that remembers previous results and supports complex operations.
   **Input:** `5 + 3 = 8, MEM, 4 * MEM = 32, CLEAR`
   **Output:** `Result: 32, Memory cleared`

5. **Number Base Converter**
   Convert numbers between different bases (2, 8, 10, 16).
   **Input:** `255 from base 10 to base 2`
   **Output:** `11111111`

6. **Perfect Number Generator**
   Find all perfect numbers up to N (number equals sum of its proper divisors).
   **Input:** `n = 100`
   **Output:** `6 28`

7. **Matrix Operations**
   Add, subtract, and multiply 2D matrices.
   **Input:** 
   ```
   Matrix A: [[1,2],[3,4]]
   Matrix B: [[5,6],[7,8]]
   Operation: multiply
   ```
   **Output:** `[[19,22],[43,50]]`

8. **Text Statistics Analyzer**
   Analyze text for words, characters, vowels, consonants, and frequency.
   **Input:** `"Hello World Programming"`
   **Output:** 
   ```
   Characters: 23, Words: 3, Vowels: 6, Consonants: 11
   Most frequent: 'r' (3 times)
   ```

9. **Number Guessing Game with AI**
   Advanced guessing game where computer learns from player patterns.
   **Input:** `Secret: 42, Guesses: 50, 25, 37, 44, 42`
   **Output:** `Found in 5 attempts! Pattern detected: binary search`

10. **Financial Calculator**
    Calculate compound interest, loan payments, and investment growth.
    **Input:** `Principal: $1000, Rate: 5%, Time: 3 years, Compound: monthly`
    **Output:** 
    ```
    Simple Interest: $150.00
    Compound Interest: $161.47
    Monthly Payment: $30.42
    Total Amount: $1161.47
    ```

---

## 🏆 Difficulty Progression

- **Beginner (Exercises 1-6):** Basic syntax, simple logic
- **Intermediate (Exercise 7):** Combining multiple concepts
- **Advanced (Exercise 8):** Complex algorithms, optimization, real-world applications

## 📚 Additional Tips

- Practice debugging with different inputs
- Focus on edge cases and error handling
- Optimize your solutions for better performance
- Use proper variable naming and code organization
- Test thoroughly with various input combinations

