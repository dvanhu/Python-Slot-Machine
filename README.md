# 🎰 Python Slot Machine Game

Welcome to the **Python Slot Machine** — a simple, text-based gambling simulation game created using Python. This project offers a fun way to practice Python fundamentals including loops, functions, conditionals, random number generation, and user input handling.

---

## 📌 Project Description

This terminal-based slot machine game allows users to:

- 💰 Deposit money
- 🎯 Choose the number of lines to bet on (1–3)
- 🎲 Place a bet per line
- 🌀 Spin a 3x3 slot machine grid
- 🏆 Win or lose money based on the results
- 💼 Track balance until the player decides to quit

It’s perfect for beginners learning **Python basics**, **randomization**, and **logic structuring**.

---

## 🧠 Game Logic

- The slot machine is a 3×3 grid.
- Each column randomly picks symbols (`A`, `B`, `C`, `D`) based on predefined frequencies (i.e., weights).
- If all symbols on a **bet line (row)** match across columns, the player wins.
- Each symbol has its own payout value.
- Winnings are added to the balance; losing lines subtract the bet.

---

## 🚀 Features

- ✅ Balance management  
- ✅ Weighted random symbol generation  
- ✅ Line-based betting (1–3 lines)  
- ✅ Symbol-based payout system  
- ✅ Clear terminal-based UI  
- ✅ Input validation and error handling  

---

## 🛠️ Technologies Used

- **Python 3**
- **Standard Libraries:**
  - `random` — for weighted symbol generation
  - `input()` — for user input and interactivity

---

## 🎮 Gameplay Preview

```console
What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $5

You are betting $5 on 2 lines. Total bet is equal to: $10

A | B | D
B | B | A
D | C | C

You won $0.
You won on lines:
Current balance is $90
