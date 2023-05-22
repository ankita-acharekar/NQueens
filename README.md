# NQueens

The N-Queens problem is a classical puzzle where the goal is to place N queens on an N x N chessboard such that no two queens attack each other.

## Problem Statement

Given an integer N, return all distinct solutions to the n-queens puzzle.

## Implementation Details

The provided code is a Java implementation of the N-Queens problem using a backtracking algorithm. It explores all possible configurations of queens on the chessboard and finds distinct solutions.

The main class `Main` provides the following methods:

- `solveNQueens(int n)`: This method takes an integer `n` as input and returns a list of distinct solutions for the N-Queens problem.
- `solve(int col, char[][] board, List<List<String>> res, int[] usedRows, int[] usedLowerDiagonal, int[] usedUpperDiagonal)`: This method is a recursive helper function that solves the N-Queens problem by backtracking.
- `construct(char[][] board)`: This method converts the char board representation into a list of strings representing a valid solution.

## Usage

To use the code, follow these steps:

1. Ensure you have Java installed on your system.
2. Copy the provided code into a Java project or file (e.g., `Main.java`).
3. Create an instance of the `Main` class.
4. Call the `solveNQueens` method, passing in the desired value of `n`.
5. Retrieve the list of distinct solutions and process them as needed.
