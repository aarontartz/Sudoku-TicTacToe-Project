# Sudoku-TicTacToe-Project
## Overview
This game was created as a final project for my COMPE-271 class (Computer Organization), with the intention
to be an introduction to coding in Assembly. This game was creating in both C++ and Assembly to demonstrate
the differing complexities between them to achieve the same goal.
## Game Description
This 2-player game is a mashup of ultimate tic-tac-toe and sudoku. Ultimate
tic-tac-toe is just like tic-tac-toe, but each square in the 3x3 grid has its own
tic-tac-toe board. Whereas in normal tic-tac-toe one simply “owns” each square
by putting an X or O in it, in ultimate tic-tac-toe, a player has to win the smaller
3x3 tic-tac-toe board. If the square is a draw, that square becomes owned by
neither player. The mashup comes in in that instead of a blank tic-tac-toe board
and players being able to go wherever they want, there is a preset 9x9 sudoku
grid they have to fill out (3x3 tic-tac-toe board with each square having their own
3x3 tic-tac-toe board) with the correct numbers. If a player gets a number wrong,
it skips their turn.