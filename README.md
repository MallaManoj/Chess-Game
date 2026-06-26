# ♟️ Chess Game

A fully functional chess game built with Python and Pygame, featuring a complete board with all chess pieces, move validation, special moves (castling, en passant, pawn promotion), and an interactive GUI.

## 🎮 Features

- **Full Chess Implementation**: Complete board setup with all 32 pieces (pawns, rooks, knights, bishops, queens, and kings)
- **Valid Move Calculation**: Intelligent move validation for each piece type with special move support
- **Special Moves**:
  - ♚ **Castling**: King and rook movement (kingside and queenside)
  - **En Passant**: Pawn capture technique
  - **Pawn Promotion**: Automatic queen promotion when reaching the last rank
- **Check Detection**: Validates moves to ensure king safety
- **Piece Dragging**: Intuitive drag-and-drop interface for moving pieces
- **Move Highlighting**: Visual indication of valid moves and last move played
- **Sound Effects**: Audio feedback for moves and captures
- **Theme Support**: Switch between different visual themes (press 'T')
- **Game Reset**: Restart the game anytime (press 'R')

## 📁 Project Structure

```
chess_python/
├── src/
│   ├── main.py           # Main game loop and event handling
│   ├── board.py          # Board logic and move validation
│   ├── game.py           # Game state and rendering
│   ├── piece.py          # Piece classes (Pawn, Knight, Bishop, Rook, Queen, King)
│   ├── square.py         # Square representation and utility methods
│   ├── move.py           # Move class for tracking piece movements
│   ├── dragger.py        # Mouse drag handling for piece movement
│   ├── config.py         # Configuration, themes, and sound setup
│   ├── color.py          # Color definitions
│   ├── const.py          # Game constants (board size, colors)
│   ├── theme.py          # Theme configuration
│   └── sound.py          # Sound utility class
├── assets/               # Game assets (sounds, piece images)
├── docs/                 # Documentation files
└── snapshots/            # Game screenshots
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Pygame library

### Installation

1. Clone the repository:
```bash
git clone https://github.com/MallaManoj/Chess-Game.git
cd Chess-Game
```

2. Install dependencies:
```bash
pip install pygame
```

3. Run the game:
```bash
python chess_python/src/main.py
```

## 🎯 How to Play

1. **Move Pieces**: Click and drag pieces to move them. Valid moves will be highlighted.
2. **Switch Themes**: Press 'T' to cycle through different board themes
3. **Reset Game**: Press 'R' to start a new game
4. **Quit**: Close the window to exit

### Chess Rules Implemented
- ♙ **Pawns**: Move forward 1 or 2 squares (first move), capture diagonally, en passant, promotion
- ♘ **Knights**: L-shaped movement (2+1 squares)
- ♗ **Bishops**: Diagonal movement
- ♖ **Rooks**: Horizontal and vertical movement
- ♕ **Queen**: Combined rook and bishop movement
- ♔ **King**: One square in any direction, castling support

## 💻 Core Components

| Component | Purpose |
|-----------|---------|
| `Board` | Manages the 8x8 grid, piece placement, and move validation |
| `Game` | Handles game state, rendering, and turn management |
| `Piece` | Base class for all chess pieces with movement logic |
| `Dragger` | Manages piece selection and drag-and-drop mechanics |
| `Config` | Stores themes, fonts, and sound effects |
| `Square` | Represents individual board squares |

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `T` | Change theme |
| `R` | Reset game |
| `ESC` | Quit game |

## 🎨 Customization

Modify game constants in `chess_python/src/const.py`:
- Board size and square size
- Colors and themes
- Window dimensions

## 📜 License

This project is open source and available under the MIT License.

## 👤 Author

**Malla Manoj**
**https://github.com/MallaManoj/Chess-Game**

---

Enjoy playing chess! ♟️
