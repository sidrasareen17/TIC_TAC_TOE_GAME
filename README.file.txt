Project Overview:

This is a simple, interactive Tic-Tac-Toe game that allows two players to play against each other. The game is played on a 3x3 grid, where one player uses "X" and the other uses "O". Players take turns to mark a square, and the first player to get three of their marks in a row (vertically, horizontally, or diagonally) wins.

Features:
Two-player mode (Player 1: X, Player 2: O)
3x3 grid layout
Validates player input and ensures that moves are within the grid and not on an already taken square
Declares the winner when one player achieves a winning combination
Displays the game board after each move
Option to restart the game after a win or draw
Installation Instructions:
Clone the repository or download the project files to your local machine.

Ensure you have Python installed (version 3.x recommended). You can download Python from https://www.python.org/.

Navigate to the project folder using the command line or terminal.

Run the Game: Open a terminal and run the following command to start the game:

Copy code
java tic_tac_toe.java


How to Play:
The game will prompt Player 1 (X) to make a move by selecting a number from 1 to 9. Each number corresponds to a cell on the 3x3 grid.

Example grid:

markdown
Copy code
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9
After Player 1 makes a move, the game will prompt Player 2 (O) to make their move.

Players alternate turns, and the game continues until either one player wins or the board is full (resulting in a draw).

The game will display the current state of the board after every move.

The game will announce the winner or if the game ends in a draw.

After a game ends, you can restart the game if you wish.

Example of Game Play:
markdown
Copy code
Player 1 (X), it's your turn!
Enter a number between 1 and 9: 5

Current Board:
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9

Player 2 (O), it's your turn!
Enter a number between 1 and 9: 1

Current Board:
X | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9

...

Player 1 (X) wins!



Game Rules:

The first player to place three of their marks in a row wins.
The game board is a 3x3 grid, and each player can place their mark ("X" or "O") in an empty space.
If the grid is full and no player has won, the game is a draw.
Code Structure:
tic_tac_toe.py: Main Python script containing the game logic.
README.txt: Documentation for the project (this file).
requirements.txt (optional): If any external libraries are used, they will be listed here.
Contributing:
Fork the repository and create a new branch for any features or bug fixes.
Make sure to write tests for any new functionality.
Submit a pull request with a detailed description of your changes.
License:
This project is licensed under the MIT License.
