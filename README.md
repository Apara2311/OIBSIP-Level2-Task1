# 🧮 Basic Calculator using HTML, CSS, and JavaScript

This project is a fully functional web-based calculator built using **HTML**, **CSS (Grid Layout)**, and **JavaScript**. It supports basic arithmetic operations as well as brackets `(` and `)` for complex expressions. The design is responsive and user-friendly.

---

## ✅ Features

- Basic operations: **Addition (+), Subtraction (−), Multiplication (×), Division (÷)**
- Bracket support: **( and )** for grouping expressions
- Decimal support using `.`
- Clear screen with **C** button
- **Responsive layout** using CSS Grid
- Clean and minimal UI

---

## 🧠 How It Works

The calculator consists of:
- A **display screen** to show inputs and results.
- **Buttons** for digits, operators, clear, equals, and brackets.
- JavaScript functions to handle input, clear the display, and evaluate expressions.

---

## 📁 Project Directory Structure



## 📁 Project Directory Structure

calculator/<br>
├── index.html<br>
│   ├── Main HTML file<br>
│   ├── Creates calculator structure: display + button grid<br>
│   ├── Links style.css (for styling)<br>
│   └── Links script.js (for logic and interactivity)<br><br>
├── style.css<br>
│   ├── Styles the calculator using CSS Grid<br>
│   ├── Sets layout, button sizes, spacing, colors, and hover effects<br>
│   └── Ensures responsive design for different screen sizes<br><br>
└── script.js<br>
    ├── appendValue(value)<br>
    │   └── Appends digits/operators to the display<br>
    ├── clearDisplay()<br>
    │   └── Clears the current input on screen<br>
    └── calculate()<br>
        └── Evaluates the expression using eval()<br>


