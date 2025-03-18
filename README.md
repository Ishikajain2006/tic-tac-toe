Tic-Tac-Toe Game

# Description

This is a simple Tic-Tac-Toe game implemented in C. The game is played on a 3x3 grid, where two players take turns marking spaces with 'X' or 'O'. The first player to get three of their marks in a row, column, or diagonal wins the game. If the grid is completely filled and no player has won, the game ends in a draw.

# Features

1.Two-player mode

2.Simple console-based UI

3.Input validation to prevent invalid moves

4.Automatic detection of win or draw conditions

# How to Play

Run the program in a C environment (e.g., GCC compiler).

The game starts with Player 'X'.

Players take turns entering a row and column number (1-3) to place their mark.

The game ends when a player wins or the board is full.

If a player wins, their victory is displayed. If the board is full without a winner, the game ends in a draw.

# Compilation and Execution

To compile the program using GCC:

gcc tic_tac_toe.c -o tic_tac_toe

To run the compiled program:

./tic_tac_toe

Example Gameplay

 1 | 2 | 3
---|---|---
 4 | 5 | 6
---|---|---
 7 | 8 | 9

Player X, enter row (1-3) and column (1-3): 1 1
 X |   |   
---|---|---
   |   |   
---|---|---
   |   |   

Player O, enter row (1-3) and column (1-3): 2 2
 X |   |   
---|---|---
   | O |   
---|---|---
   |   |   

# Future Improvements

Add a computer AI opponent

Enhance the UI with a graphical interface

Implement a restart option after a game ends


