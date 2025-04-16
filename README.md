# Java Calculator with Exception Handling

## 🧮 Description
This is a simple calculator application built in Java. It performs basic arithmetic operations such as addition, subtraction, multiplication, division, square, cube, and square root.

Each operation is implemented in a **separate Java file** using static methods, and **exception handling** is used to catch runtime errors like division by zero or square root of negative numbers.

---

## 📁 File Structure

| File | Description |
|------|-------------|
| `Main.java` | Contains the main logic and menu-driven interface |
| `Addition.java` | Handles addition of two numbers |
| `Subtraction.java` | Handles subtraction |
| `Multiplication.java` | Handles multiplication |
| `Division.java` | Handles division with division-by-zero handling |
| `Square.java` | Computes square of a number |
| `Cube.java` | Computes cube of a number |
| `SquareRoot.java` | Computes square root with negative number check |

---

## 🧾 Features
- Menu-based interface
- Exception handling for:
  - Division by zero
  - Square root of negative numbers
- Clean modular design (one file per operation)
- Beginner-friendly

---

## 🛠️ How to Run

### 1. Compile all Java files:
```bash
javac *.java
