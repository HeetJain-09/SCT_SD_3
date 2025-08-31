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
## Example Input Grid


grid = [
  [5,3,0,0,7,0,0,0,0],
  [6,0,0,1,9,5,0,0,0],
  [0,9,8,0,0,0,0,6,0],
  [8,0,0,0,6,0,0,0,3],
  [4,0,0,8,0,3,0,0,1],
  [7,0,0,0,2,0,0,0,6],
  [0,6,0,0,0,0,2,8,0],
  [0,0,0,4,1,9,0,0,5],
  [0,0,0,0,8,0,0,7,9]
]

## Example Output


[[5 3 4 6 7 8 9 1 2]
 [6 7 2 1 9 5 3 4 8]
 [1 9 8 3 4 2 5 6 7]
 [8 5 9 7 6 1 4 2 3]
 [4 2 6 8 5 3 7 9 1]
 [7 1 3 9 2 4 8 5 6]
 [9 6 1 5 3 7 2 8 4]
 [2 8 7 4 1 9 6 3 5]
 [3 4 5 2 8 6 1 7 9]]
