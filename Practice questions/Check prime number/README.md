# Prime Number Checker (Java)

A simple Java console application that checks whether a given number is a **Prime Number** or **Not a Prime Number** using a loop and conditional statements.

## 📌 Features

- Accepts user input from the keyboard.
- Checks if the entered number is prime.
- Handles numbers less than or equal to 1.
- Displays whether the number is prime or not.
- Beginner-friendly Java program.

## 🛠️ Technologies Used

- Java
- Scanner Class (`java.util.Scanner`)

## 📂 Project Structure

```
Module1/
└── PrimeCheck.java
```

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```

2. Navigate to the project folder:
   ```bash
   cd your-repository-name
   ```

3. Compile the program:
   ```bash
   javac Module1/PrimeCheck.java
   ```

4. Run the program:
   ```bash
   java Module1.PrimeCheck
   ```

## 💻 Sample Output

### Example 1

```
Enter a number: 17
17 is a Prime Number.
```

### Example 2

```
Enter a number: 20
20 is not a Prime Number.
```

## 📖 How It Works

1. Reads an integer from the user.
2. Checks if the number is less than or equal to 1.
3. If not, checks divisibility from `2` to `n/2`.
4. If any divisor is found, the number is not prime.
5. Otherwise, the number is declared prime.

## 🎯 Learning Concepts

- Java Basics
- Conditional Statements (`if-else`)
- Loops (`for`)
- Boolean Variables
- User Input using `Scanner`

## 📄 License

This project is open source and available under the MIT License.
