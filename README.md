# Sudoku 
This is a simple **Sudoku** game implemented using HTML, CSS, and JavaScript. Players can solve a predefined Sudoku puzzle by selecting numbers and placing them in the appropriate cells. The game validates player inputs and tracks errors.
##### Play here: [https://sudoku-harshithaxkatakams-projects.vercel.app/]

## Features

- **Interactive Board**: A 9x9 Sudoku board where players can fill in numbers.
- **Number Selection**: A number panel allows players to select digits (1-9) to place on the board.
- **Validation**: Checks if the selected number is correct based on the solution.
- **Error Tracking**: Displays the number of errors made by the player.
- **Pre-filled Cells**: The game starts with certain cells pre-filled to provide a challenge.
- **Responsive Design**: Board includes grid lines to visually distinguish 3x3 sections for better gameplay.

## Requirements

- A modern web browser that supports JavaScript.
- Basic knowledge of Sudoku rules to play the game.

## How to Run

1. Copy the code into an `index.html` file.
2. Add accompanying CSS and JavaScript if necessary, or place all the code in a single HTML file.
3. Open the file in any modern web browser.
4. The game will load, and you can begin solving the Sudoku puzzle.

## Controls

- **Number Selection**: Click on a number from the panel (1-9) to select it.
- **Tile Selection**: Click on any empty tile on the Sudoku board to place the selected number.

## Game Rules

1. The goal of Sudoku is to fill a 9x9 grid such that each row, column, and 3x3 section contains all digits from 1 to 9 without repetition.
2. Use the number panel to select a digit and place it on the board by clicking on an empty tile.
3. If the placed number matches the solution, it remains on the board.
4. If the placed number is incorrect, an error is recorded and displayed.
5. The game ends when the puzzle is correctly completed.

## Code Highlights

- **Dynamic Board Creation**: The Sudoku board is dynamically generated using JavaScript and styled with CSS.
- **Validation**: The game checks player inputs against a predefined solution array (`solution`).
- **Error Handling**: Errors are counted and displayed in real-time as players make incorrect moves.
- **Grid Design**: Horizontal and vertical grid lines are added to visually separate 3x3 sections of the board for clarity.

## Customization

- **Puzzle Difficulty**: Modify the `board` array in the code to create puzzles of varying difficulty.
- **Solution**: Update the `solution` array to match the new puzzle.
- **Styles**: Customize colors, fonts, and grid design in the CSS to change the game's appearance.

## Screenshots

### Initial Game Screen
- Displays the Sudoku board with some cells pre-filled and the number panel on the side.

### Gameplay
- Players select numbers from the panel and place them on the board.
- Incorrect placements increase the error count displayed on the screen.

### Completed Puzzle
- The game ends when all cells are correctly filled, and no empty tiles remain.

---

## Enjoy Playing!

Test your Sudoku-solving skills with this interactive game!

![sudoku-preview](https://user-images.githubusercontent.com/78777681/163041771-71dd9cfd-7c94-424a-bdc9-4c252ccd66a8.png)
