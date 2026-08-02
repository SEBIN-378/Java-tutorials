# Leap Year Checker (Java)

A simple Java console application that checks whether a given year is a **Leap Year** or **Not a Leap Year** using conditional statements.

## 📌 Features

- Accepts a year as user input.
- Determines whether the year is a leap year.
- Uses standard leap year rules.
- Beginner-friendly Java program.

## 🛠️ Technologies Used

- Java
- Scanner Class (`java.util.Scanner`)

## 📂 Project Structure

```
Module1/
└── LeapYear.java
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
   javac Module1/LeapYear.java
   ```

4. Run the program:
   ```bash
   java Module1.LeapYear
   ```

## 💻 Sample Output

### Example 1

```
Enter a year: 2024
2024 is a Leap Year.
```

### Example 2

```
Enter a year: 2023
2023 is not a Leap Year.
```

## 📖 How It Works

1. Reads a year from the user.
2. Checks if the year is divisible by `400`.
3. If not, checks whether it is divisible by `4` but not by `100`.
4. Displays whether the year is a leap year or not.

## 🎯 Learning Concepts

- Java Basics
- Conditional Statements (`if-else`)
- Logical Operators (`&&`, `||`)
- Modulo Operator (`%`)
- User Input using `Scanner`

## 📄 License

This project is open source and available under the MIT License.
