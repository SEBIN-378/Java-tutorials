# Java Calculator

A simple Java console-based calculator that performs basic arithmetic operations using the `switch` statement.

## 📌 Description

This program allows the user to:
- Enter two numbers.
- Choose an arithmetic operator (`+`, `-`, `*`, `/`).
- Perform the selected operation.
- Display the result.
- Handle division by zero and invalid operators gracefully.

## 🚀 Features

- Addition
- Subtraction
- Multiplication
- Division
- Division by zero validation
- Invalid operator handling
- User-friendly console interface

## 🛠️ Technologies Used

- Java
- Scanner Class
- Switch Statement

## 📂 Project Structure

```
Calculator.java
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, VS Code, etc.).

3. Compile the program:
   ```bash
   javac Calculator.java
   ```

4. Run the program:
   ```bash
   java Calculator
   ```

## 💻 Sample Output

### Example 1: Addition
```
Enter first number: 15
Enter second number: 10
Enter operator (+, -, *, /): +
Result = 25.0
```

### Example 2: Division
```
Enter first number: 20
Enter second number: 4
Enter operator (+, -, *, /): /
Result = 5.0
```

### Example 3: Division by Zero
```
Enter first number: 10
Enter second number: 0
Enter operator (+, -, *, /): /
Division by zero is not possible.
```

### Example 4: Invalid Operator
```
Enter first number: 10
Enter second number: 5
Enter operator (+, -, *, /): %
Invalid Operator
```

## 📚 Concepts Covered

- User Input using `Scanner`
- Switch Statement
- Arithmetic Operators
- Conditional Statements (`if-else`)
- Exception Prevention (Division by Zero)

## 👨‍💻 Author

**Sebin Raju**

---
⭐ If you found this project helpful, consider giving the repository a star!








# Odd Numbers in Java

A simple Java program that prints all odd numbers from **1** to a user-specified limit using a `for` loop and the `continue` statement.

## 📌 Description

This program:
- Accepts an integer `n` from the user.
- Iterates from `1` to `n`.
- Skips even numbers using the `continue` statement.
- Prints only the odd numbers.

For example:
- Input: `10`
- Output: `1 3 5 7 9`

## 🚀 Features

- Takes user input using `Scanner`
- Uses a `for` loop for iteration
- Uses the `continue` statement to skip even numbers
- Simple and beginner-friendly Java program

## 🛠️ Technologies Used

- Java
- Scanner Class
- For Loop
- Continue Statement

## 📂 Project Structure

```
OddNumbers.java
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, VS Code, etc.).

3. Compile the program:
   ```bash
   javac OddNumbers.java
   ```

4. Run the program:
   ```bash
   java OddNumbers
   ```

## 💻 Sample Output

```
Enter n: 10
1 3 5 7 9
```

## 📚 Concepts Covered

- User Input
- For Loop
- Conditional Statements
- Modulus Operator (`%`)
- Continue Statement

## 👨‍💻 Author

**Sebin Raju**

---

⭐ If you found this project helpful, consider giving the repository a star!





# Palindrome Number in Java

A simple Java program that checks whether a given integer is a **palindrome** by reversing its digits and comparing the reversed number with the original.

## 📌 Description

This program:
- Accepts an integer from the user.
- Reverses the digits using a `while` loop.
- Compares the reversed number with the original number.
- Displays whether the number is a palindrome or not.

For example:
- Input: `121`
- Output: `Palindrome Number`

## 🚀 Features

- Takes user input using `Scanner`
- Reverses a number using a `while` loop
- Checks if the number is a palindrome
- Simple and beginner-friendly Java program

## 🛠️ Technologies Used

- Java
- Scanner Class
- While Loop
- Conditional Statements

## 📂 Project Structure

```
PalindromeNumber.java
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, VS Code, etc.).

3. Compile the program:
   ```bash
   javac PalindromeNumber.java
   ```

4. Run the program:
   ```bash
   java PalindromeNumber
   ```

## 💻 Sample Output

### Example 1
```
Enter a number: 121
Palindrome Number
```

### Example 2
```
Enter a number: 123
Not a Palindrome Number
```

## 📚 Concepts Covered

- User Input
- While Loop
- Integer Arithmetic
- Modulus Operator (`%`)
- Conditional Statements (`if-else`)

## 👨‍💻 Author

**Sebin Raju**

---

⭐ If you found this project helpful, consider giving the repository a star!




# Sum of Digits in Java

A simple Java program that calculates the **sum of the digits** of a number entered by the user using a `while` loop.

## 📌 Description

This program:
- Accepts a four-digit number from the user.
- Extracts each digit using the modulus (`%`) operator.
- Adds the digits together.
- Displays the total sum of the digits.

> **Note:** Although the prompt asks for a four-digit number, the program works correctly for any positive integer.

For example:
- Input: `1234`
- Output: `10`

## 🚀 Features

- Takes user input using `Scanner`
- Calculates the sum of digits using a `while` loop
- Simple and beginner-friendly Java program
- Works for any positive integer

## 🛠️ Technologies Used

- Java
- Scanner Class
- While Loop

## 📂 Project Structure

```
SumOfDigits.java
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, VS Code, etc.).

3. Compile the program:
   ```bash
   javac SumOfDigits.java
   ```

4. Run the program:
   ```bash
   java SumOfDigits
   ```

## 💻 Sample Output

```
Enter a four-digit number: 1234
Sum of digits = 10
```

## 📚 Concepts Covered

- User Input
- While Loop
- Integer Arithmetic
- Modulus Operator (`%`)
- Division Operator (`/`)

## 👨‍💻 Author

**Sebin Raju**

---

⭐ If you found this project helpful, consider giving the repository a star!




# Vowel or Consonant in Java

A simple Java program that determines whether a character entered by the user is a **vowel** or a **consonant** using a `switch` statement.

## 📌 Description

This program:
- Accepts a single character from the user.
- Converts the character to lowercase for case-insensitive comparison.
- Uses a `switch` statement to check whether the character is a vowel.
- Displays whether the entered character is a vowel or a consonant.

For example:
- Input: `A`
- Output: `Vowel`

## 🚀 Features

- Takes user input using `Scanner`
- Supports both uppercase and lowercase letters
- Uses a `switch` statement for decision-making
- Simple and beginner-friendly Java program

> **Note:** This program assumes the user enters an English alphabet character. If a digit or special character is entered, it will be treated as a consonant.

## 🛠️ Technologies Used

- Java
- Scanner Class
- Switch Statement
- Character Class (`Character.toLowerCase()`)

## 📂 Project Structure

```
VowelOrConsonant.java
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, VS Code, etc.).

3. Compile the program:
   ```bash
   javac VowelOrConsonant.java
   ```

4. Run the program:
   ```bash
   java VowelOrConsonant
   ```

## 💻 Sample Output

### Example 1
```
Enter a character: A
Vowel
```

### Example 2
```
Enter a character: z
Consonant
```

## 📚 Concepts Covered

- User Input
- Switch Statement
- Character Handling
- Case Conversion
- Conditional Logic

## 👨‍💻 Author

**Sebin Raju**

---

⭐ If you found this project helpful, consider giving the repository a star!





# Fibonacci Series in Java

A simple Java program that prints the **Fibonacci series** up to a specified number of terms using a `for` loop.

## 📌 Description

This program:
- Accepts the number of terms (`n`) from the user.
- Generates the Fibonacci sequence starting with `0` and `1`.
- Prints the first `n` terms of the series.

The Fibonacci sequence is formed by adding the two previous numbers to get the next number.

For example:
- Input: `7`
- Output: `0 1 1 2 3 5 8`

## 🚀 Features

- Takes user input using `Scanner`
- Generates the Fibonacci sequence using a `for` loop
- Efficient iterative approach
- Simple and beginner-friendly Java program

## 🛠️ Technologies Used

- Java
- Scanner Class
- For Loop

## 📂 Project Structure

```
FibonacciSeries.java
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Open the project in your preferred Java IDE (IntelliJ IDEA, Eclipse, VS Code, etc.).

3. Compile the program:
   ```bash
   javac FibonacciSeries.java
   ```

4. Run the program:
   ```bash
   java FibonacciSeries
   ```

## 💻 Sample Output

```
Enter n: 7
0 1 1 2 3 5 8
```

## 📚 Concepts Covered

- User Input
- For Loop
- Variables
- Iterative Programming
- Fibonacci Sequence Logic

## 👨‍💻 Author

**Sebin Raju**

---

⭐ If you found this project helpful, consider giving the repository a star!
