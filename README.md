# 2048 Game
This project is a simple, browser-based implementation of the popular 2048 game. Use the arrow keys to slide numbered tiles on a grid. When two tiles with the same number touch, they merge into one tile with double the number. The goal of the game is to create a tile with the number 2048.

<h2>Game Rules</h2>
Use the arrow keys to move tiles: Up, Down, Left, Right.
When two tiles with the same number touch, they merge into one with the number doubled.
Each turn, a new tile will randomly appear in an empty spot on the board with a value of either 2 or 4.
Game will be over if there are no empty spots on the board for 4 consecutive turns.

<h2>Setup & Running the Game</h2>
Clone the repository to your local machine.
Open the index.html file in your browser to start the game.
Technical Details

<h2>This version of 2048 is implemented using JavaScript and is organized as follows:</h2>
script.js: Contains the main game logic.
Grid.js: Defines the Grid class which represents the game board. It's responsible for managing the cells on the board and their states.
Tile.js: Defines the Tile class which represents an individual tile on the grid. It's responsible for managing the tile value and its state.
The game starts by creating a new Grid object and then two Tile objects in random empty cells. setupInput() sets up an event listener for arrow keys to handle player input.

The handleInput() function takes the player's key press, checks if the intended movement is valid, and if so, moves all tiles accordingly and spawns a new tile in a random empty cell. The game ends when there are no valid moves left.

<h2>License</h2>
This project is open source, under the MIT License.
