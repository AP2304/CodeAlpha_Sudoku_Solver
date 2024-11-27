# Sudoku_Solver
I developed this Sudoku solver  using C++

## Problem Statement

Sudoku is a popular logic-based puzzle game. The puzzle consists of a 9x9 grid, which is subdivided into nine 3x3 subgrids. Some cells are pre-filled with numbers, while others are empty. The goal is to fill the empty cells with numbers from 1 to 9, such that:

- Each row contains all digits from 1 to 9 without repetition.
- Each column contains all digits from 1 to 9 without repetition.
- Each of the nine 3x3 subgrids contains all digits from 1 to 9 without repetition.

This program takes a partially filled Sudoku grid as input and attempts to solve the puzzle using a backtracking algorithm. If a solution exists, the program will fill in the missing numbers and output the solved grid. If no solution exists, the program will inform the user that the puzzle is unsolvable.

### Input

- A partially filled 9x9 Sudoku grid where each cell is either a number from 1 to 9 or 0 (representing an empty cell).
  
### Output

- If a solution exists, the program will output the solved 9x9 Sudoku grid.
- If no solution is found, the program will display a message indicating that no solution exists.
