# Tic Tac Toe Game

This is a simple command-line based Tic Tac Toe game implemented in Python. The game allows two players, "X" and "O", to take turns placing their marks on the board until one player wins or the game ends in a tie.

## Board Representation

The game board is represented as a list of strings, where each string represents a cell on the board. An empty cell is denoted by "-", and when a player makes a move, their mark ("X" or "O") is placed in the corresponding cell.


## Functions

1. `printBoard(board)`: This function prints the current state of the board.

2. `playerInput(board)`: This function takes user input to get the cell number (1-9) where the current player wants to place their mark. If the chosen cell is valid and available, the player's mark is placed in that cell; otherwise, an error message is displayed, and the player switches turn.

3. `checkHorizontal(board)`: This function checks if there is a winning combination in any of the horizontal rows.

4. `checkRow(board)`: This function checks if there is a winning combination in any of the vertical columns.

5. `checkDiagonal(board)`: This function checks if there is a winning combination in either of the two diagonals.

6. `checkTie(board)`: This function checks if the game is a tie, i.e., if all the cells are filled and no player has won.

7. `checkForWin()`: This function calls the three functions mentioned above to check if the game has been won by any player.

8. `switchPlayer()`: This function switches the current player after each turn.

## How to Play

1. The game starts with an empty board.

2. The board is displayed after each player makes a move.

3. Players are prompted to enter a number between 1 and 9 to select the cell where they want to place their mark. The cells are numbered as follows:


4. To place a mark, enter the corresponding cell number.

5. The game continues until one player wins or the game ends in a tie.

6. When the game ends, the winner or the tie result will be displayed.

## How to Run

1. Copy the entire code into a Python file (e.g., `tictactoe.py`).

2. Open a terminal or command prompt.

3. Navigate to the directory containing the `tictactoe.py` file.

4. Run the game by executing the Python script:

```bash
python tictactoe.py
