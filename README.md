"""
Sudoku Solver using Backtracking Algorithm

This Python program solves a standard 9x9 Sudoku puzzle.
It uses the backtracking algorithm to recursively attempt
filling in the grid with valid numbers (1–9), ensuring
each row, column, and 3x3 sub-grid contains no duplicates.

Key Functions:
--------------
- print_grid(grid): Nicely prints the Sudoku grid.
- find_empty(grid): Returns the next empty cell (denoted by 0).
- is_valid(grid, num, pos): Checks if a number can be placed
  at a given position according to Sudoku rules.
- solve(grid): Applies backtracking to solve the puzzle.

Usage:
------
Define a 9x9 grid (`sudoku_grid`) with zeros representing empty cells.
Call solve(sudoku_grid) to fill in the missing values.
The result is printed if a solution exists.

Example:
--------
Unsolved Sudoku:
5 1 7 6 0 0 0 3 4
...
Solved Sudoku:
5 1 7 6 9 8 2 3 4
...

Author: [Your Name]
Date: [YYYY-MM-DD]
"""
