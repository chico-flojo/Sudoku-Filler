# Project Phase-1 Submission

## Team Number : 
1

## Team Members : 
Himansh Mudigonda

Bharath Sanikommu

Dadi Hemasri

## Project Title : 
Auto-Sudoku Solver.

## Project Description : 
In this project we create a brainy sudoku solver using the Backtracking algorithm.

## Approach : 
In this project we would use the Backtracking algorithm to solve the sudoku puzzle. Backtracking lets us solve the sudoku problem while exhausting all possible combinations of inputs(1 to 9) in the problem. This enables us to solve any sudoku, with any difficulty.

## STEP Wise Algorithm : 
STEP 1 : Find a block that has no predefined number.

STEP 2 : Return a positive boolean result if all blocks are filled.

STEP 3 : Run a loop running ‘$order_of_matrix’ times

STEP 4a: Assign a digit, that is not already assigned in the row or column or the respective sub-domain, to the block.

STEP 4b: If the digit cannot be filled in the block, the subtree is nullified and the possibility is removed.

STEP 4c: Move on to the next iteration.

STEP 4d: This process is repeated till the criteria of “STEP 2” is fulfilled.

STEP 5 : Return a negative boolean result if none of the digits can be placed in a block(which breaks out of the backtracking algorithm).



