Sure, here's a README file for the given code:

# Tic-Tac-Toe Game

## Introduction

This Python program is a simple implementation of the classic Tic-Tac-Toe game. The game is played on a 3x3 board where two players, "you" (the user) and "me" (the computer), take turns to mark the cells with "O" and "X" respectively. The objective is to place three of your marks in a horizontal, vertical, or diagonal row to win the game.

## Requirements

- Python 3.x

## How to Run

1. Save the code in a file, for example, `tic_tac_toe.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where the file is saved.
4. Run the command: `python tic_tac_toe.py`.

## Functions

### `display_board(board)`

- **Parameters:** `board` - A 3x3 list representing the game board.
- **Description:** This function displays the current state of the game board.

### `enter_move(board)`

- **Parameters:** `board` - A 3x3 list representing the game board.
- **Description:** This function prompts the user to enter their move, validates the input, and updates the board accordingly.

### `make_list_of_free_fields(board)`

- **Parameters:** `board` - A 3x3 list representing the game board.
- **Returns:** A list of tuples representing the free cells on the board.
- **Description:** This function generates a list of free cells available for marking.

### `victory_for(board, sgn)`

- **Parameters:** 
  - `board` - A 3x3 list representing the game board.
  - `sgn` - A character ('O' or 'X') representing the player's mark.
- **Returns:** A string indicating the winner ('me', 'you', or `None` for no winner).
- **Description:** This function checks if the specified player has won the game.

### `draw_move(board)`

- **Parameters:** `board` - A 3x3 list representing the game board.
- **Description:** This function makes a random move for the computer and updates the board.

## Game Flow

1. The game starts with the computer placing an "X" in the middle of the board.
2. The user is prompted to enter their move.
3. The computer makes a random move.
4. The game alternates between the user and the computer until all cells are filled or a player wins.
5. The final state of the board is displayed, and the winner is announced.

## Example Output

```
+-------+-------+-------+
|       |       |       |
|   1   |   2   |   3   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   4   |   X   |   6   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   7   |   8   |   9   |
|       |       |       |
+-------+-------+-------+
Enter your move: 
```

## Author

Feel free to edit and improve this README file as needed. Have fun playing Tic-Tac-Toe! 🎮
