The aim of this project is to create a simple console-based Tic-Tac-Toe game using Python. This game involves two players taking turns to place their markers (either 'X' or 'O') on a 3x3 grid with the goal of aligning three of their markers in a row, column, or diagonal to win. The project demonstrates basic concepts in Python programming such as handling user input, managing game logic, and implementing functions to check for win conditions and update the game board.

Key Details:
Game Board Representation:

The game board is represented as a 3x3 list of lists where each cell can be empty or contain a player's marker ('X' or 'O').
Marker Assignment:

Players are prompted to choose their markers. Player 1 chooses 'X' or 'O', and Player 2 automatically receives the opposite marker.
User Input:

Players input their move by specifying coordinates (x, y) which correspond to the cell where they want to place their marker.
Win Condition Check:

The game includes functions to check for winning conditions: three markers in a row, column, or diagonal.
Turn Management:

The game alternates turns between the two players. It continues until a player wins or the game ends in a draw.
Game Termination:

The game ends when one player wins. The board and game status are updated to reflect the outcome.
Error Handling:

The code includes basic error handling for invalid marker choices and coordinates.
