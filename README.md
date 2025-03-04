# Tic Tac Toe

## Summary
This C program is a simple implementation of the classic game "Tic Tac Toe." The player competes against the computer, with the player using `X` and the computer using `O`. The game is played on a 3x3 grid, and the objective is to get three of your symbols in a row (horizontally, vertically, or diagonally) before the opponent does. The program includes features such as resetting the board, checking for a winner, handling player and computer moves, and allowing the player to replay the game.

## Features
- **Board Representation**: The game uses a 3x3 grid (`board[3][3]`) to represent the Tic Tac Toe board.
- **Player and Computer Moves**: The player inputs their move by specifying the row and column numbers, while the computer's move is randomly generated using the `rand()` function.
- **Win Condition Checking**: The program checks for a winner after each move by examining rows, columns, and diagonals for three matching symbols.
- **Draw Condition**: If all spaces on the board are filled and no winner is found, the game ends in a draw.
- **Replayability**: The player can choose to play again after each game by entering `Y` or exit by entering `N`.
- **Input Validation**: The program ensures that the player's move is valid (i.e., within the bounds of the board and on an empty space).
- **Randomized Computer Moves**: The computer's moves are randomized using the `srand()` and `rand()` functions, seeded with the current time.

## How to Play
1. Run the program in a C environment.
2. The player is prompted to enter the row and column numbers (1-3) for their move.
3. The computer will automatically make its move after the player.
4. The game continues until either the player or the computer wins, or the board is filled (resulting in a draw).
5. After the game ends, the player can choose to play again or exit.

## Requirements
- A C compiler (e.g., GCC) to compile and run the program.

## Running the Program
To run the program, follow these steps:
1. Save the code to a file (e.g., `tic_tac_toe.c`).
2. Compile the program using a C compiler:
   ```bash
   gcc tictactoe.c -o tictactoe
   ```
