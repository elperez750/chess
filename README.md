# Python Chess Game

A classic chess game implemented in Python using the Pygame library. This project offers a fully functional chess game with a graphical user interface, allowing players to enjoy the timeless strategy game on their computer.

## Features

- Full implementation of chess rules, including special moves like castling, en passant, and pawn promotion
- Graphical user interface using Pygame
- Two-player mode (local multiplayer)
- Move validation to ensure only legal moves are allowed
- Check and checkmate detection
- Simple and intuitive controls

## Requirements

- Python 3.7+
- Pygame 2.0+

## Installation

1. Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. Install Pygame using pip:

3. Clone this repository or download the source code:


## How to Play

1. Run the game:

  
3. The game window will open, displaying the chess board with pieces in their starting positions.

4. Players take turns making moves:
- Click on a piece to select it
- Valid moves will be highlighted
- Click on a highlighted square to move the selected piece

4. Special moves:
- Castling: Move the king two squares towards a rook
- En passant: Capture a pawn that has just moved two squares forward
- Pawn promotion: When a pawn reaches the opposite end of the board, it will automatically promote to a queen

5. The game ends when one player achieves checkmate or when a stalemate occurs.

## Controls

- Left mouse button: Select and move pieces
- ESC: Quit the game

## Project Structure

- `chess_game.py`: Main game file, contains the game loop and Pygame initialization
- `chess_engine.py`: Chess logic implementation, including move validation and game state
- `assets/`: Directory containing image files for chess pieces and the board

## Contributing

Contributions to improve the game are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Chess piece images from [Chess.com](https://www.chess.com/)
- Pygame community for their excellent documentation and examples

## Future Improvements

- Add an AI opponent
- Implement a move history feature
- Add a timer for timed games
- Include sound effects for moves and game events

Enjoy your game of chess!
