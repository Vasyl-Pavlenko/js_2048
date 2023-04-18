# Game 2048

This is a simple implementation of the popular game 2048 using JavaScript and HTML/CSS. The game board is a 4x4 grid, and the goal is to reach the number 2048 by merging tiles with the same numbers.

## Features

- Move tiles in four directions: left, right, up, and down using arrow keys.
- Merge tiles with the same numbers to create new tiles with a sum of their values.
- Randomly generate new tiles (2 or 4) after each move.
- Keep track of the current score and display it on the scoreboard.
- Display win or lose messages when the game ends.
- Reset the game to start a new game.

## Getting Started

1.  Clone the repository to your local machine.
2.  Open the `index.html` file in a web browser.
3.  Use arrow keys (left, right, up, down) to move the tiles on the game board.
4.  Try to merge tiles with the same numbers to reach 2048.
5.  Game ends when the game board is full and no further moves are possible or when the player reaches 2048.
6.  You can reset the game by clicking the "New Game" button.

## Code Overview

The game logic is implemented in JavaScript (`script.js`) and uses DOM manipulation to update the game board and interact with the user interface. The key components of the code are:

- `gameTable`: a 2D array representing the game board with initial values of 0.
- `keyCode`: an object that defines the key codes for arrow keys.
- `makeMove()`: a function that handles the logic for moving tiles in different directions.
- `connect()`: a function that handles the logic for merging tiles with the same numbers.
- `gameEnd()`: a function that checks if the game has ended.
- `addScore()`: a function that calculates and updates the current score.
- `action()`: a function that triggers a move in a specific direction and updates the game state.
- Event listeners: listening for arrow key presses and click events on the "New Game" button.

## Please check my preview link:

- [DEMO LINK](https://vasyl-pavlenko.github.io/js_2048)

## Repository link on github:

- [GITHUB](https://github.com/Vasyl-Pavlenko/js_2048)
