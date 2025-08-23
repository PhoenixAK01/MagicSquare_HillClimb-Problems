# MagicSquare_HillClimb-Problems

Magic Square Generator
This program generates a magic square of order n (where n ≥ 3 and n ≠ 2).
A magic square is an n × n matrix filled with distinct positive integers from 1 to n² such that the sum of each row, column, and both main diagonals is the same. This sum is known as the magic constant.
Time Complexity:O(n²),Space Complexity: O(n²)

Hill Climbing Algorithm for 8-Puzzle
Features
Uses misplaced tiles heuristic as the cost function.
Explores neighboring states by moving the empty tile in four directions (up, down, left, right).
Stops when no better neighbor is found (local maxima or plateau).
Prints the steps taken, including the board configuration and heuristic after each move.
Time Complexity:O(k * 4 * 9) ≈ O(k), where k is the number of states visited.
Space Complexity:O(1)
