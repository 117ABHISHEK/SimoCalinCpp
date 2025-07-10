
# 🧮 Simple Calculator (C++)

This is a console-based **Simple Calculator** written in C++. It can perform basic arithmetic operations like **Addition**, **Subtraction**, **Multiplication**, and **Division** on two numbers entered as an inline equation (e.g., `5+3` or `10/2`).

---

## 📌 Features

- Handles:
  - `+` Addition
  - `-` Subtraction
  - `*` Multiplication
  - `/` Division (with zero division check)
- Takes input in the format: `number operator number` (e.g., `8*4`)
- Gracefully exits on typing `exit` or `EXIT`
- Simple instructions screen
- Auto-repeats for multiple calculations
- Input parsing using `stringstream`

---

## 🛠️ Technologies Used

- C++ (Standard Library)
- `iostream`, `string`, and `sstream` for input handling
- Object-Oriented Programming using classes

---

## 🚀 How to Run

### 📌 Prerequisites:
- C++ compiler (`g++` recommended)

### ▶️ Compile and Run:

```bash
g++ -o calculator calculator.cpp
./calculator
```

You’ll see the welcome screen, and you can start typing equations like:

```
5+3
12.4/2
8*7
exit
```

---

## ⚠️ Instructions

1. Input must be in this format: `number operator number` (e.g., `12+3`)
2. No parentheses `()` or brackets `[]` are allowed.
3. It is **case-sensitive** and expects proper input formatting.
4. To **exit**, type `exit` or `EXIT`.

---

## 📸 Demo

```
==================== Simple Calculator ====================
========== -:INSTRUCTIONS :- ==========
1. This is a Simple Calculator which can only perform simple Addition,
   Subtraction, Multiplication, and Division.
2. This is case-sensitive. Use proper inputs, otherwise, it may give wrong output.
   Don't use brackets like (), []

Enter the equation :-  8*9
The ans of the Eq is : 8*9 = 72
```

---

## 🙌 Contribution

Feel free to fork and enhance the features like:
- Adding support for parentheses
- Multi-operator parsing
- GUI or CLI enhancement
- Error handling for invalid equations

---

## 👨‍💻 Author

- **Abhishek** 
