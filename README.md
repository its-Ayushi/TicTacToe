
# Tic-Tac-Toe Game

This is a simple implementation of the classic **Tic-Tac-Toe** game in Python. Players take turns to mark their respective symbols ("X" or "O") on a 3x3 grid. The first player to align three of their symbols horizontally, vertically, or diagonally wins the game. If all squares are filled without a winner, the game ends in a draw.

## Features
- Two-player turn-based gameplay (Player 1 with "X" and Player 2 with "O").
- Ability to check the game status and declare a winner or a draw.
- A simple console-based interface that prints the game board after each move.

## Requirements
- Python 3.x

## How to Play

1. Clone or download the repository.
2. Open a terminal or command prompt.
3. Run the Python file:
   ```bash
   python tic_tac_toe.py
   ```
4. Players will alternate entering a number between 1 and 9, corresponding to the position on the 3x3 grid.
   - 1 | 2 | 3
   - 4 | 5 | 6
   - 7 | 8 | 9

5. After each move, the updated board will be displayed.
6. The game will automatically end when there is a winner or when the grid is full (draw).

## Game Status
- The game will check after every move:
  - If a player wins, it will announce the winner.
  - If all squares are filled without a winner, it will declare a draw.
  - The game continues if no one wins and there are still moves available.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/tic-tac-toe.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd tic-tac-toe
   ```

3. **Run the game script:**
   ```bash
   python tic_tac_toe.py
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
