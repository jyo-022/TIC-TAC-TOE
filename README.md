Tic Tac Toe Game 🎮

Project Description-

This project is a Tic Tac Toe game built using Python. It supports two modes:

1. Player vs Computer – The computer makes random moves.
2. Player vs Player – Two players can compete against each other.

The game checks for a win or draw condition after each move and provides real-time feedback on the game state.

Features:
Two game modes: Player vs Computer and Player vs Player
Win detection and draw handling
Simple command-line interface for an interactive experience
Random move generator for the computer

How It Works:
1. The game board is represented as a list with 9 spaces.
2. Players take turns entering their moves (1–9).
3. The computer randomly selects its move in Player vs Computer mode.
4. The game checks for a winner after each turn using the is_victory() function.
5. If no winner is found and the board is full, it declares a draw.

Code Explanation:
print_board(): Displays the current state of the game board.
player_move(icon): Handles player moves and checks for valid inputs.
player_movec(icon): Generates a random move for the computer.
is_victory(icon): Checks for winning combinations.
is_draw(): Checks if the board is full (indicating a draw).

Installation and Usage:
1. Clone the repository or download the code.
2. Ensure that Python 3.x is installed on your system.
3. Run the script using the command:
      python tic_tac_toe.py
4. Follow the on-screen instructions to play the game.



Sample Output:

TIC-TAC-TOE

|   |   |   |
|   |   |   |
|   |   |   |

Player 1's turn (X). Enter your move (1-9):

Requirements:
Python 3.x
