# Python Chess Game

A fully functional chess game implemented in Python using Pygame. This project demonstrates object-oriented programming concepts, game development principles, and chess rules implementation.

## Features

- Complete chess game with all standard rules
- Visual board representation using Pygame
- Support for all chess pieces with custom graphics
- Valid move highlighting
- Special moves implementation:
  - Castling
  - En Passant
  - Pawn Promotion
- Game state tracking:
  - Check detection
  - Checkmate detection
  - Stalemate detection
- Interactive piece selection and movement
- Visual feedback for selected pieces and valid moves

## Requirements

- Python 3.x
- Pygame

## Installation

1. Clone the repository:
```bash
git clone https://github.com/strothon/chess.git
cd chess
```

2. Install the required dependencies:
```bash
pip install pygame
```

3. Run the game:
```bash
python chess.py
```

## Implementation Details

### Key Classes

1. **Piece**: Base class for all chess pieces
   - Implements common piece functionality
   - Handles piece movement validation
   - Manages piece graphics

2. **Board**: Manages the game board
   - Handles piece placement and movement
   - Validates moves
   - Tracks game state
   - Implements special chess rules

3. **ChessGame**: Main game class
   - Manages the game loop
   - Handles user input
   - Renders the game state
   - Implements the UI

### Learning Points

1. **Object-Oriented Programming**
   - Inheritance and polymorphism with piece classes
   - Encapsulation of game logic
   - Class relationships and design patterns

2. **Game Development**
   - Game loop implementation
   - Event handling
   - Graphics rendering
   - User input processing

3. **Chess Rules Implementation**
   - Move validation
   - Special move handling
   - Game state management
   - Check and checkmate detection

4. **Python Best Practices**
   - Code organization
   - Error handling
   - Resource management
   - Performance optimization

## How to Play

1. Click on a piece to select it
2. Valid moves will be highlighted
3. Click on a highlighted square to move the piece
4. For pawn promotion, select the desired piece from the promotion menu
5. The game will automatically detect check, checkmate, and stalemate

## Future Enhancements

* Move history display
* Save/load game functionality
* Multiplayer support (local or online)
* AI opponent implementation
* Sound effects
* Move timer
* Game settings menu

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* Chess piece images sourced from the `resources/` directory.
* Pygame library for graphics and input handling.
* Inspiration and resources from the Python community.
