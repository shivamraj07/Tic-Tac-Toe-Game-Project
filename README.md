# Tic-Tac-Toe Game
### Project Overview
This project is a Tic-Tac-Toe game built using HTML, CSS, and JavaScript. It allows two players to play the classic game of Tic-Tac-Toe in a web browser. The game features a responsive design and can be played on both desktop and mobile devices.

> Demo :- 

### Features
- Two-Player Mode: Supports two players, one playing as "X" and the other as "O".
- Win Detection: Automatically detects when a player wins or when the game ends in a draw.
- Restart Game: Players can reset or restart the game board to start a new game.
- Responsive Design: The game board adjusts to different screen sizes for both desktop and mobile devices.
- Game Status Display: Shows the current player's turn and the result of the game (win/draw).
### Technologies Used
- HTML: Provides the structure of the game board and status display.
- CSS: Styles the game board, buttons, and overall layout for a clean and responsive design.
- JavaScript: Handles the game logic, including player turns, win conditions, and board resets.

### Installation
1. Clone the repository:
git clone https://github.com/your-username/tic-tac-toe.git

2. Navigate to the project directory:
cd tic-tac-toe

3. Open the project: Open index.html in your preferred browser.

### How to Play
1. Start the Game:

- The game starts with Player X's turn.
- Players take turns clicking on empty squares to mark their symbol ("X" or "O").

2. Winning the Game:
- A player wins by placing three of their marks in a horizontal, vertical, or diagonal row.
- The game automatically checks for winning combinations after each move and displays a win message for the winning player.

3. Draw:
- If all squares are filled without a winner, the game ends in a draw, and a draw message is displayed.

4. Restart Game:
- Press the "Restart" button to clear the board and start a new game.


### File Details
- index.html:

  - Contains the game board structure with a 3x3 grid of buttons or divs representing the Tic-Tac-Toe squares.
  - Also includes a display section to show the game status (e.g., player's turn, win message).

- style.css:
  - Styles the layout of the game, including the game board, buttons, and text.
  - Provides responsiveness so the game board adjusts to different screen sizes.

- script.js:
- Implements the game logic, including:
  - Switching between players.
  - Detecting win conditions (3 marks in a row).
  - Displaying the result (win or draw).
  - Resetting the game for a new round.

### Customization
You can customize the Tic-Tac-Toe game by modifying the following:

1. Change Player Symbols:
- You can change the default "X" and "O" to other symbols, such as emojis, in the script.js file.

2. Board Size:
- You can modify the grid size to create a larger Tic-Tac-Toe game (e.g., 4x4 or 5x5) by adjusting the HTML structure and the game logic in script.js.

3. Styling:
- Customize the look and feel of the game by updating style.css with new colors, fonts, or button styles.

### Future Enhancements
- Score Tracking: Implement a scoring system that tracks wins and draws over multiple games.

- Sound Effects: Add sound effects for player moves, wins, and draws.




