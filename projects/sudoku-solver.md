---
layout: project
type: project
image: images/sudokupic.jpg
title: Sudoku Solver
permalink: projects/sudokuSolver
# All dates must be YYYY-MM-DD format!
date: 2020-03-01
labels:
  - Java
  - Recurisve backtracking
  - Programming
  - Learning
summary: A program that finds the solution to a Hexadecimal Sudoku problem from course ICS 211.
---

## Hexadecimal Sudoku Solver

During my Spring semester of 2020, one homework assignment we did for ICS 211 was a Hexadecimal Recursive Sudoku Solver. Which used recursive backtracking to solve a 16x16 sudoku puzzle. We were helped by our professor Cam Moore, who set up the assignment for us and were tasked with creating solveSudoku and legalValues functions. 

## Short Explanation

First when looking at the solveSudoku function it checked the puzzle input and empty cells were shown with a -1. The legalValues function then is used by the solveSudoku, creating a list of possible legal values. Then this is repeated as it recursively calls itself until either it is able to solve the sudoku puzzle, or if it encounters a cell with no legal value backtracks to the last cell it encountered and tries the next legal value. Then again it will continue to solve or decide that the puzzle is not solvable. 

## Experience

This was a great learning experience for me as prior to this, I had barely a clue about recursive topics at all. I do think that my ability to think recursively still has a long way to go, however I think projects like these that are challenging are definitely helping me to develop. 
