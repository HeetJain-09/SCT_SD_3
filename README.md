# SCT_SD_3
Repository containing software development TASK 3

------------------
## SkillCraft Technology Internship Task


This project was completed as part of my Software Development Internship at SkillCraft Technology. It demonstrates solving a Sudoku puzzle using a recursive backtracking algorithm implemented in Python.

---------------------
## Task 03: Sudoku Solver
This program solves a standard 9x9 Sudoku puzzle automatically.

It takes an input Sudoku grid with empty cells and applies a backtracking algorithm to fill in missing numbers while respecting Sudoku rules.

------------
## How It Works
- Uses recursion and backtracking to explore possible values for empty cells.

- Checks if placing a number violates Sudoku constraints in row, column, and 3x3 subgrid.

- Fills each empty cell with a valid number and continues recursively.

Backtracks if a chosen number leads to contradiction.

- Prints the solved Sudoku grid using NumPy for matrix formatting.

----------------------

 ## Requirements
 - Python 3

- NumPy library

- Install NumPy using:
pip install numpy

--------------------------
## How to Run
1. Run the  notebook.

2. The Sudoku grid to solve is predefined in the code as a list of lists (0 represents an empty cell).

3. The solution is printed as a formatted matrix.

-----------------------------
