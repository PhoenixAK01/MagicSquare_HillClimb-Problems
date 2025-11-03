HillClimb-Problems

Hill Climbing Algorithm for 8-Puzzle
Features
Uses misplaced tiles heuristic as the cost function.
Explores neighboring states by moving the empty tile in four directions (up, down, left, right).
Stops when no better neighbor is found (local maxima or plateau).
Prints the steps taken, including the board configuration and heuristic after each move.
Time Complexity:O(k * 4 * 9) ≈ O(k), where k is the number of states visited.
Space Complexity:O(1)

Magic Square
Algorithm Details
Odd Order Magic Squares (n odd)
Implemented using the Siamese method (also known as the De la Loubère algorithm).
Steps:
Start from the middle of the top row.
Place consecutive numbers, moving up and right.
Wrap around edges.
If the target cell is filled, move one cell left.
Time Complexity: O(n²)
Space Complexity: O(n²)

Doubly Even Order Magic Squares (n % 4 == 0)
Implemented using the Strachey method.
Steps:
Fill the matrix sequentially from 1 to n².
Then invert numbers at certain positions based on (i % 4) and (j % 4) patterns.
Time Complexity: O(n²)
Space Complexity: O(n²)

Singly Even Order Magic Squares (n % 4 == 2)
Constructed using a combination method:
Divide the square into 4 quadrants of size (n/2 × n/2).
Fill quadrants using an odd-order magic square.
Add offsets (n²/4, n²/2, 3n²/4) to form full square.
Swap columns based on Strachey’s rules.
Time Complexity: O(n²)
Space Complexity: O(n²)
