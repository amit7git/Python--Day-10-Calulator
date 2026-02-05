# Day 10 – Calculator 🧮

Part of my **100 Days of Python Projects** challenge.  
This project is a console-based calculator that performs basic arithmetic operations and allows continuous calculations using previous results.

---

## 🚀 Project Overview
The Calculator Project is a Python console application that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

The calculator can:
- Continue calculating using the current result
- Start a new calculation
- Exit when the user chooses

This project focuses on strengthening concepts like functions, recursion, dictionaries, and user input handling.

---

## 📚 What I Learned
- Writing **functions with return values** to make logic reusable  
- Using **multiple return values** when needed  
- Understanding and writing **docstrings** for better code readability  
- Implementing **recursion** to restart the calculator  
- Mapping operators to functions using **dictionaries**  
- Handling user input safely inside loops  

---

## 🛠 How It Works
1. The program displays an ASCII calculator logo (from the `art` module)  
2. The user enters the first number  
3. The program shows available operations: `+`, `-`, `*`, `/`  
4. The user selects an operator  
5. The user enters the next number  
6. The program performs the selected operation  
7. The result is displayed  
8. The user chooses whether to:
   - Continue with the current result (`y`)
   - Start a new calculation (`n`)
   - Exit the program (`exit`)

The program runs continuously until the user exits.

---

## 💡 Code Highlights
- Used a **dictionary** to map operators (`+`, `-`, `*`, `/`) to their respective functions  
- Organized logic using **nested functions**  
- Implemented **recursion** to restart the calculator cleanly  
- Used a `while` loop for continuous interaction  
- Applied **input validation** for smoother user experience  

---

## 🧪 Example
    
    Enter the first number: 10
    +
    
    /
    Pick an operation: *
    Enter the next number: 5
    
    10 * 5 = 50
    
    Type 'y' to continue calculating with 50,
    'n' to start a new calculation,
    or 'exit' to quit: y
    
    50 + 20 = 70


---

## ▶️ How to Run
1. Clone the repository  
2. Open the project folder  
3. Run the file using:
4. Follow the on-screen prompts  

---

## 🌐 Live Demo
[https://github.com/amit7git/Python--Day-10-Calculator](https://amit7git.github.io/Python--Day-10-Calulator/)

