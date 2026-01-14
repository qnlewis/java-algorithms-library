# ☕ Java Algorithmic Utilities

A library of optimized logical solutions and data structure manipulations implemented in Java. This project demonstrates mastery of strict typing, memory management, and algorithmic efficiency.

### 🎯 The Problem
The goal was to build a robust library of common computer science algorithms—ranging from mathematical sequences to string manipulation—that handles edge cases (null inputs, negative numbers) gracefully without crashing.

### 🛠 Tech Stack
* **Language:** Java 21 (Maven)
* **Testing:** JUnit 5
* **Core Concepts:** Recursion, String Manipulation, Control Flow, `StringBuilder` optimization

### ✨ Key Features
* **FizzBuzz Engine:** A modular implementation of the classic interview problem using `List<String>` for testability rather than direct console output.
* **Recursive Math:** Includes a factorial calculator that handles large numbers using `long` to prevent integer overflow.
* **String Analysis:** A palindrome checker that efficiently ignores punctuation and casing using regex `[^A-Za-z0-9]` and two-pointer traversal.
* **Pattern Generation:** Generates complex ASCII shapes (pyramids/triangles) using nested loops and `StringBuilder` for memory efficiency.

### 💻 How to Run
1. **Test the library:**
   ```bash
   mvn test
2. **Compile:**
   ```bash
   mvn clean compile
