---
layout: project
type: project
image: images/HexSudoku.jpg
title: Hexadecimal Sudoku Solver
permalink: projects/hexadecimalSudoku
# All dates must be YYYY-MM-DD format!
date: 2018-03-26
labels:
  - Java
  - recursion
  - backtracking
  - game
summary: A Hexadecimal Sudoku Solver for my ICS 211 class. 
---

This project was a homework assignment for my ICS 211 class. Dr. Moore, my professor for this class, provided the code for formatting and setting up the sudoku grid and created restrictions to prevent illegal values. This is a program written in Java that solves 16 x 16 sudoku grids. For the puzzle to be considered solved, each row, column, and grid must only contain one of each number (1-9) and letter (A-F). 

The solveSudoku() method takes one ```int[][]```, which represents the unsolved sudoku grid, as the parameter. This solveSudoku() method only checks if the grid is valid, and recursively calls the nextEmpty() and solveCell() methods to eventually solve the whole grid. The nextEmpty() method finds the next empty cell and calls solveCell() to solve it. The solveCell() method solves the cell and calls the nextEmpty() method to find and solve the next cell. These methods recurse until the grid is filled. The program uses a brute force approach by trying all of the possible solutions and backtracking when contradictions arise. 

This project helped me to better understand and visualize recursion, while also introducing me to new concepts, such as backtracking. 

View the source code [here](https://github.com/kathleen808/hexadecimal-sudoku). 
