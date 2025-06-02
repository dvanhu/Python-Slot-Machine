# 🎰 Python Slot Machine Game

Welcome to the **Python Slot Machine** — a simple, text-based gambling simulation game created using Python. This project is a fun way to understand Python fundamentals like loops, functions, conditionals, random number generation, and basic user input handling.

---

## 📌 Project Description

This terminal-based slot machine game allows a user to:

- Deposit money
- Choose the number of lines to bet on (1–3)
- Place a bet per line
- Spin a 3x3 slot machine grid
- Win or lose money based on the result
- Track balance and repeat until the player decides to quit

It is an ideal beginner-friendly project to practice **Python basics**, **randomization**, and **logic structuring**.

---

## 🧠 Game Logic

- The slot machine is a 3x3 grid (3 rows × 3 columns).
- Each column randomly picks symbols (`A`, `B`, `C`, `D`) with weighted probability using a predefined count.
- If all symbols on a bet line (row) match across columns, the player wins.
- Payouts are determined by the value assigned to each symbol.
- Winnings are added to the balance; losses are subtracted.

---

## 🚀 Features

- ✅ User balance handling
- ✅ Random symbol generation with frequency control
- ✅ Line-based betting system (1–3 lines)
- ✅ Winnings calculation per symbol type
- ✅ Dynamic terminal output
- ✅ Input validation and error handling

---

## 🛠️ Technologies Used

- **Python 3**
- Standard libraries:
  - `random` for symbol generation
  - `input()` for user interaction

---

## 🎮 Gameplay Preview
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

