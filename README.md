# TicTacToe_Java
Tic Tac Toe game with 2 players
This Java code is for a basic Tic Tac Toe game that can be played between two players. 
The game interface is displayed in a window, and players take turns clicking on the empty cells to place their respective marks ('X' or 'O'). 
The first player to align three marks horizontally, vertically, or diagonally wins the game. If all cells are filled without any player winning, the game ends in a draw.

Key components
JFrame class: a top-level window that hosts the game interface.
JPanel class: a container for holding components.
JLabel class: a component used to display text on the interface.
JButton class: a component that is used as the clickable cells on the interface.
ActionListener interface: used for responding to button click events.
Random class: used to randomly decide which player gets to go first.
The main class is called TicTacToe, which implements the ActionListener interface. The TicTacToe constructor sets up the window, panels, and buttons. It also calls startGame() to randomly decide which player gets to go first. The ActionListener interface is implemented to handle the button click events.

The matchCheck() method is called after each move to check if any player has won the game. This method uses conditional statements to check for all possible win conditions.

The gameOver() method is called when the game ends. It displays a message indicating the winner or a tie and gives the players the option to restart or exit the game.

How to use
To use this code, copy and paste it into a Java IDE and run it. The game interface should appear in a new window. 
Players can take turns clicking on the empty cells to place their respective marks. 
The game ends when a player wins or when all cells are filled without any player winning. 
At the end of the game, a message will appear indicating the winner or a tie and giving the players the option to restart or exit the game.
