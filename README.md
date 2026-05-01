# CodeAlpha_Task-SudokuSolver
# 🧩 Sudoku Solver (C++)
A console-based Sudoku Solver built in C++ that solves a 9×9 Sudoku puzzle using the **Backtracking Algorithm**. The program takes an incomplete Sudoku grid as input and outputs the solved puzzle if a valid solution exists.
##  Overview
This project demonstrates the use of recursion and backtracking to solve constraint-based problems like Sudoku. It also includes validation to ensure that the given input grid follows Sudoku rules before attempting to solve it.
##  Features

-  Solves 9×9 Sudoku using Backtracking  
-  Validates input grid before solving  
-  Checks row, column, and 3×3 subgrid constraints  
-  User input for custom Sudoku puzzles  
-  Displays both original and solved Sudoku  
-  Handles invalid or unsolvable puzzles  



##  Technologies Used

- C++
- Standard Library (`iostream`)

---

##  How It Works

### 1. Input Phase
- User enters a 9×9 Sudoku grid  
- Use `0` for empty cells  

### 2. Validation
- Checks whether the initial grid is valid according to Sudoku rules:
  - No duplicate numbers in rows  
  - No duplicate numbers in columns  
  - No duplicate numbers in 3×3 subgrids  

### 3. Solving Algorithm
- Uses **Backtracking**:
  - Find an empty cell  
  - Try numbers from 1–9  
  - Check if placement is valid  
  - Recursively solve remaining grid  
  - Backtrack if no valid number works  

---

##  Project Structure
sudoku-solver/
-main.cpp
-README.md
## Sample Input
Enter Sudoku (9x9) use 0 for empty cells:

5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9

##  Sample Output
5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9
## 👨‍💻 Author

**Laraib Qadeer**  
BS Software Engineering Student  


