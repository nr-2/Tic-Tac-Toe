### Tic-Tac-Toe Game

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [How to Play](#how-to-play)
4. [Requirements](#requirements)
5. [How to Run](#how-to-run)
6. [Project Structure](#project-structure)
7. [Customization](#customization)
8. [License](#license)

## Overview
This project is a **Tic-Tac-Toe** game built using plain HTML, CSS, and JavaScript. It features a classic 3x3 grid where two players (X and O) take turns to mark their respective symbols on the board. The game can be played in the browser with a sleek **cyberpunk** design, making it visually engaging.

## Features
- Two-player game (Player X and Player O).
- Responsive design that works on both desktop and mobile devices.
- Instant result announcement when a player wins or if the game ends in a tie.
- Reset functionality to allow replaying the game without refreshing the page.
- Stylish **cyberpunk** theme with neon colors and glowing effects.

## How to Play
1. The game starts with **Player X's** turn.
2. Players take turns by clicking on an empty tile to place their mark (X or O).
3. The game checks for a win or a tie after each move:
   - A player wins if they can line up three of their marks horizontally, vertically, or diagonally.
   - The game results in a tie if all tiles are filled without any player winning.
4. The result is displayed on the screen, and the game is over.
5. You can reset the game anytime by pressing the **Reset** button.

## Requirements
- Any modern web browser (Chrome, Firefox, Edge, etc.).
- No additional libraries or dependencies are required.

## How to Run
1. Clone or download the project files to your local machine.
   ```bash
   git clone https://github.com/nr-2/tic-tac-toe.git
   ```
2. Open the `index.html` file in your web browser.
3. Start playing!

### Alternatively:
- If you have a live server, serve the project via a local server and access it through `localhost`.

## Project Structure
Here’s how the project files are organized:

```
|-- index.html       # HTML file that contains the game structure
|-- style.css        # CSS file that styles the game in a cyberpunk theme
|-- index.js         # JavaScript file with the game logic
```

### Key Files:
1. **index.html**: Contains the basic structure of the game, including the grid (tiles), player display, and reset button.
2. **style.css**: Defines the visual appearance of the game, using neon colors and a cyberpunk theme.
3. **index.js**: Implements the game’s logic, including handling player turns, checking for wins/ties, and resetting the game.

### Game Logic Breakdown (index.js):
- **Board Setup**: The game board is represented as an array of 9 elements (for the 9 tiles).
- **Player Turn**: The current player is tracked, and it alternates between 'X' and 'O'.
- **Win Conditions**: The game checks for eight possible win conditions (horizontal, vertical, and diagonal).
- **Result Announcement**: When a player wins or the game ends in a tie, a message is displayed.
- **Reset Functionality**: Resets the game board and UI to allow a new game to start.

## Customization
You can easily customize the game by modifying the following:
- **Game Design**: Modify the `style.css` file to change the theme, colors, fonts, and layout of the game.
- **Game Rules**: You can change the win conditions or add new features (like a scoreboard) by modifying the `index.js` file.
  
### Example Customization:
#### Change the Player Symbols:
If you want to use different symbols (like emojis) instead of 'X' and 'O', you can modify the `currentPlayer` variable in the `index.js` file:
```js
let currentPlayer = '😊'; // Use emojis instead of 'X' or 'O'
```

#### Modify the Grid Size:
You can modify the grid size to make larger versions of Tic-Tac-Toe (e.g., 4x4 or 5x5) by changing the `winningConditions` and adjusting the grid in the HTML.

## License
This project is open-source and available under the **MIT License**.

---

Feel free to fork, modify, and use this project as you like! If you encounter any issues or have suggestions for improvements, feel free to open a pull request or issue on the repository.

Enjoy playing Tic-Tac-Toe! 😊

---

