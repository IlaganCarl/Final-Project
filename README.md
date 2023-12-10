**Overview of Tic Tac Toe Game**

**1. Initialization and Setup**
  
  Pygame Initialization: The Pygame library is imported and initialized to create a game window.
  Window Dimensions: The dimensions of the game window, line width, and the window caption are set.
  Colors and Font: RGB values for colors (red, green, blue) and a font object for displaying text are defined.

**2. Game Variables**
 
  Player and Clicked Flags: Variables to keep track of the current player (1 or -1) and whether the mouse has been clicked.
  Position and Markers: Variables to store the mouse position and a 3x3 grid (markers) representing the Tic Tac Toe board.
  Game Over and Winner: Flags indicating whether the game is over and the winner (1 for Player 1, 2 for Player 2, 0 for a tie).

**3. Board and Graphics Setup**

Play Again Rectangle: A rectangle is defined to represent the "Play Again" button's position and dimensions.
Grid Creation: A 3x3 grid is created using nested loops to initialize the markers list with zeros.

**4. Drawing Functions**

draw_board Function: Draws the Tic Tac Toe game board with grid lines.
draw_markers Function: Draws X and O markers on the board based on the values in the markers grid.
draw_game_over Function: Displays the game over screen, showing the winner or a tie, and the "Play Again?" option.

**5. Game Logic**

check_game_over Function: Checks for win conditions in rows, columns, and diagonals. Also checks for a tie.
Main Game Loop: Handles events, such as mouse clicks, to update the game state and check for a win or tie.

**6. Main Loop and Event Handling**
Event Handling: Monitors events such as mouse clicks and game exit events.
Game State Updates: Updates the game state based on mouse clicks, toggling players and checking for a win or tie.

**7. Display Update and Game Quit**

Display Update: Updates the display to reflect changes in the game state.
Game Quit: Exits the game loop when the window is closed.

**8. Running the Game**

The entire code is wrapped in a while loop to continuously update and display the game until the player closes the window.

**9. Play Again Functionality**

If the game is over, the "Play Again" button allows the player to reset the game state and play again.
**Conclusion**

This code provides a basic implementation of a two-player Tic Tac Toe game using the Pygame library in Python. It includes functionalities for drawing the game board, handling player moves, checking for a win or tie, and offering the option to play again.

**Group Members:**

**Carl David Ilagan**

Programmer - 40%

**Neo Francis Alday**

Troubleshooter - 30%

**Jonnel Andy Barreda**

Beta Tester - 30%