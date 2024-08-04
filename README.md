# Sudoku Game

This is a simple Sudoku game implemented using Python's Tkinter library. The game allows players to fill in the Sudoku grid and check for any duplicate numbers in rows, columns, and blocks.

## Features

- **Randomly Generated Grid:** The game generates a random Sudoku grid.
- **Interactive UI:** Players can click on cells and input numbers.
- **Check Functionality:** A button to check for duplicate numbers in rows, columns, and blocks. If duplicates are found, the corresponding cells are highlighted in red.

## Project Structure

- **`mnf1` and `mnf2`:** These variables hold the main and nested frames for the Sudoku grid layout.
- **`lbs`:** List of all the labels (cells) in the grid.
- **`chk_horz`, `chk_vert`:** Functions to check for duplicate numbers in horizontal and vertical directions, respectively.
- **`chk_v`:** Main function that checks for duplicates and highlights them.

## How to Run

### Prerequisites

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

### Running the Application

1. **Clone the repository:**
   git clone https://github.com/Gdivyabharathi/Sudoku_tk_sample.git
   cd sudoku-game
Run the application:

Copy code
python sudoku.py
Note: Replace sudoku.py with the actual name of your Python file.

Instructions:

Click on a cell and type a number (1-9).
Click the "Check" button to validate the grid. Any duplicates in rows, columns, or blocks will be highlighted in red.
Key Bindings
Number keys (0-9): Set the selected cell's value.
