
# Tic-Tac-Toe Game

## Overview

This is a simple Tic-Tac-Toe game implemented using Python's `tkinter` library for graphical user interface. It supports two players, keeps track of scores, and allows players to reset the game.

## Features

- Play against another player on the same device.
- Automatic detection of win conditions and draws.
- Score tracking for each player.
- Game reset functionality.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.
- `tkinter` library (comes pre-installed with Python).

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/tic-tac-toe.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd tic-tac-toe
   ```

3. **Run the game:**

   ```bash
   python tic_tac_toe.py
   ```

## How to Play

1. Click on any empty cell to place your mark (X or O).
2. The game will automatically check for a winner or a draw.
3. The current player's turn will be displayed at the bottom.
4. The game score is displayed on the right side.
5. Click the "Reset" button to start a new game.

## Code Overview

- **`check_winner()`**: Checks if there is a winner or if the game is a draw.
- **`button_click(index)`**: Handles button clicks and updates the game state.
- **`toggle_player()`**: Switches the current player.
- **`update_scores()`**: Updates the score display.
- **`reset_game()`**: Resets the game board and state.

## Screenshots
![Screenshot 2024-08-26 172416](https://github.com/user-attachments/assets/50d086c3-e26d-4a1a-998b-9268ae34d64f)
![Screenshot 2024-08-26 173102](https://github.com/user-attachments/assets/f52eeb16-0132-4c37-b03f-fa7bf557552b)
![Screenshot 2024-08-26 173302](https://github.com/user-attachments/assets/ab7ef9d5-68c9-4cff-93c5-a264483998d9)

## Contributing

Feel free to fork the repository and make your own improvements. If you find any bugs or have suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The game uses the `tkinter` library for the graphical user interface.
