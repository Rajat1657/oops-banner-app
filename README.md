# OOPS Banner App (UC6)

## Description
OOPS Banner App (UC6) is a Java console application that renders the word **"OOPS"** as an ASCII banner.

This version refactors the banner logic into separate functions to improve modularity, readability, and maintainability.

---

## Author
Rajat  

Version: 6.0

---

## Objective
- Demonstrate method creation in Java
- Refactor repetitive logic into reusable functions
- Use `String.join()` for formatted output
- Apply structured and modular programming principles

---

## Program Structure

### 1. main()
- Calls `buildLine()` for each row (0–6)
- Stores results in an array
- Prints each line using a for-each loop

### 2. buildLine(int row)
- Assembles a full banner row
- Combines letter patterns using `String.join()`

### 3. Letter Pattern Methods
- `getOPattern(int row)`
- `getPPattern(int row)`
- `getSPattern(int row)`

Each method:
- Stores the ASCII design of the letter in an array
- Returns the appropriate row based on the index

---

## Key Concepts Used
- Method creation and reuse
- Functional decomposition
- Arrays
- `String.join()`
- Enhanced for-loop
- Clean code structure

---

## Requirements
- Java 8 or higher

---

## How to Compile and Run

### Compile:
```bash
javac OOPSBannerApp.java
```

### Run:
```bash
java OOPSBannerApp
```

---

## Output
The program prints a structured ASCII banner of the word:

OOPS