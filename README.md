# C++ Programming Internship

NAME: Nilay Sinha
Roll No: 25SCS1003003510  
B.Tech CSE
Section 2CSE34
IILM University
Session 2025–29

This repository contains the two C++ projects completed as part of the **CodeAlpha C++ Programming Internship**:

1. [Banking Management System](#1-banking-management-system)
2. [Sudoku Solver](#2-sudoku-solver)

## 1. Banking Management System

A console-based C++ application that simulates core banking operations — built to create and manage customer accounts while maintaining balances and transaction records.

### Features
- Create a new account with a unique account number
- Deposit and withdraw funds
- Transfer funds between accounts
- View account details and balance
- Maintain a full transaction history
- Close an account (subject to conditions)
- Persistent storage using file handling

### Technologies & Concepts
- C++ (Classes & Objects, OOP)
- Functions, conditionals, loops
- File I/O (`accounts.txt`, `transactions.txt`)
- Input validation and basic error handling

### How to Compile & Run
```bash
cd BankingManagementSystem
g++ banking.cpp -o banking
./banking
```

### Sample Test Cases
| Test Case | Expected Result |
|---|---|
| Create a new account | Account created with a unique number |
| Deposit a valid amount | Balance increases correctly |
| Withdraw more than balance | Transaction rejected |
| Transfer between valid accounts | Amount deducted & credited correctly |
| Close account with balance | Closure rejected |

---

## 2. Sudoku Solver

A C++ program that solves a standard 9×9 Sudoku puzzle using a **recursive backtracking algorithm**. Empty cells are represented by `0`.

### Features
- Accepts a 9×9 Sudoku grid as input
- Validates row, column, and 3×3 sub-grid constraints
- Solves the puzzle using recursion + backtracking
- Reports if no solution exists
- Optional HTML/CSS front-end for grid display (visual only — solving logic runs in C++)

### Core Functions
| Function | Purpose |
|---|---|
| `findEmptyCell()` | Finds the next empty position in the grid |
| `isSafe()` | Checks row, column & 3×3 sub-grid rules |
| `solveSudoku()` | Recursion + backtracking to solve the puzzle |
| `printGrid()` | Displays the grid in a readable format |

### How to Compile & Run
```bash
cd SudokuSolver
g++ sudoku.cpp -o sudoku
./sudoku
```

Enter the puzzle row by row, using `0` for empty cells.

### Sample Input
```
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

### Sample Test Cases
| Test Case | Expected Result |
|---|---|
| Provide a solvable puzzle | Solved grid displayed |
| Provide an unsolvable puzzle | "No solution" reported |
| Check invalid placement | Number rejected per Sudoku rules |

---

## Technologies & Concepts Used (Overall)

| Concept / Technology | Application |
|---|---|
| C++ | Primary language for both projects |
| Object-Oriented Programming | Organizing banking accounts & operations |
| Classes & Objects | Modeling accounts and their behaviour |
| Functions | Breaking programs into reusable tasks |
| File Handling | Storing account & transaction data |
| Arrays / Data Structures | Representing the Sudoku grid |
| Recursion & Backtracking | Solving Sudoku systematically |
| Input Validation | Preventing invalid values & operations |

---

## Learning Outcomes
- Strengthened C++ fundamentals and program structure
- Applied object-oriented programming to a real application
- Practiced file handling for persistent data storage
- Understood recursion and backtracking through a constraint-based problem
- Improved debugging, testing, and code organization skills

## Future Scope
- Add a graphical user interface to both applications
- Replace text-file storage with a database
- Add authentication and role-based access to the banking system
- Add Sudoku difficulty levels and puzzle generation
- Expand automated testing and documentation

---

## Author

**Nilay Sinha**
B.Tech CSE, Section 2CSE34, Session 2025–29
IILM University
Internship Organization: **CodeAlpha**

## Documents

- [`Internship_Report.pdf`](./Internship_Report.pdf) — full internship report covering both projects
- [`Internship_Presentation.pdf`](./Internship_Presentation.pdf) — internship presentation slides
