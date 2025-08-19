HillClimb-Problems

Hill Climbing Algorithm for 8-Puzzle
Features
Uses misplaced tiles heuristic as the cost function.
Explores neighboring states by moving the empty tile in four directions (up, down, left, right).
Stops when no better neighbor is found (local maxima or plateau).
Prints the steps taken, including the board configuration and heuristic after each move.
Time Complexity:O(k * 4 * 9) ≈ O(k), where k is the number of states visited.
Space Complexity:O(1)
