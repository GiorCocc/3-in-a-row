# 🎯 3-in-a-Row Puzzle Game

![Python](https://img.shields.io/badge/python-3.6+-blue.svg)
![License](https://img.shields.io/badge/license-GPL-green.svg)
![Game](https://img.shields.io/badge/type-puzzle-orange.svg)

A challenging matrix-based puzzle game where strategy meets logic! 🧩 Fill the grid with black and white cells while following strict placement rules.

## 📖 Description

3-in-a-Row is an engaging puzzle game developed as part of the Computer Science and Programming Laboratory course at the University of Parma. The game challenges players to fill a matrix with black and white cells while adhering to specific logical constraints.

**🎮 Game Concept**: Think of it as a cross between Sudoku and binary puzzles - you need to place black and white cells strategically to complete the grid without violating any rules!

## 🎯 Game Rules

The puzzle follows three fundamental rules:

1. **⚖️ Equal Distribution**: Black and white cells must be present in equal numbers (50-50 split)
2. **🚫 No Empty Cells**: All cells must be filled - no gray (empty) cells allowed in the final solution  
3. **🔢 No Three in a Row**: You cannot have three consecutive cells of the same color (horizontally or vertically)

## 🚀 Installation

### Prerequisites

- Python 3.6 or higher
- tkinter (usually comes with Python)
- pygame (will be installed automatically if needed)

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/GiorCocc/3-in-a-row.git
   cd 3-in-a-row
   ```

2. **Install dependencies** (if needed):
   ```bash
   pip install pygame
   ```

3. **Run the game**:
   ```bash
   python three_in_a_row.py
   ```

## 🎮 How to Play

### Starting the Game
- Run `three_in_a_row.py`
- Select your preferred matrix size: **6×6**, **8×8**, **10×10**, **12×12**, or **14×14**
- The game board will appear with an empty grid

### Controls
- **🖱️ Mouse Click**: Select and cycle through cell states
  - Gray (empty) → White → Black → Gray...
- **⌨️ Keyboard Shortcuts**:
  - `A` - **Auto-assist**: Fill one cell at a time with logical deduction
  - `U` - **Validate**: Check if current colored cells follow the rules
  - `H` - **Auto-solve**: Complete the entire puzzle using backtracking

### Winning
Complete the grid following all three rules to win! 🏆

## 🛠️ Technology Stack

- **Language**: Python 3.6+
- **GUI Framework**: Pygame + Tkinter
- **Algorithm**: Backtracking for auto-solving
- **Testing**: Python unittest framework

## 📁 Project Structure

```
3-in-a-row/
├── three_in_a_row.py      # Main game logic and Three class
├── boardgame.py           # Abstract base class for board games
├── boardgamegui.py        # GUI framework integration
├── g2d.py                 # 2D graphics utilities
├── g2d_pyg.py            # Pygame-specific graphics implementation
├── test.py               # Unit tests for game logic
├── config.txt            # Game configurations and presets
├── config_simple.txt     # Simplified configuration
├── p5_mat_fifteen.py     # Additional puzzle (15-puzzle)
└── README.md             # This file
```

## 🧪 Testing

Run the unit tests to verify game logic:

```bash
python test.py
```

The test suite includes:
- ✅ Cell state validation
- ✅ Rule compliance checking  
- ✅ Win condition verification
- ✅ Backtracking algorithm validation

## ✨ Features

- 🎯 **Multiple Difficulty Levels**: Choose from 5 different board sizes
- 🧠 **Smart Assistance**: AI-powered hints and auto-solving
- ✅ **Real-time Validation**: Instant feedback on rule compliance
- 🎨 **Clean Interface**: Intuitive click-to-play design
- 🔄 **Backtracking Solver**: Advanced algorithm for puzzle completion
- 📊 **Configuration System**: Customizable game presets

## 🤝 Contributing

We welcome contributions to make this game even better! Here's how you can help:

### Ways to Contribute
- 🐛 **Bug Reports**: Found an issue? Please report it!
- 💡 **Feature Suggestions**: Have ideas for new features?
- 🔧 **Code Improvements**: Submit pull requests for enhancements
- 📚 **Documentation**: Help improve our documentation
- 🎨 **UI/UX**: Suggest interface improvements

### Getting Started
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Style
- Follow PEP 8 Python style guidelines
- Add comments for complex logic
- Include unit tests for new features
- Update documentation as needed

## 📜 License

This project is licensed under the GNU General Public License v3.0 - see the [GPL License](http://www.gnu.org/licenses/gpl.html) for details.

## 🙏 Acknowledgments

- **[Michele Tomaiuolo](https://github.com/tomamic)** - Original creator of the board game framework libraries (`g2d.py`, `g2d_pyg.py`, `boardgame.py`, `boardgamegui.py`)
- **University of Parma** - Computer Science and Programming Laboratory course
- **Contributors** - Thank you to everyone who has contributed to this project!

## 🆘 Troubleshooting

### Common Issues

**Game won't start - Missing tkinter**:
```bash
# Ubuntu/Debian
sudo apt-get install python3-tk

# macOS (with Homebrew)
brew install python-tk

# Windows
# tkinter comes with Python by default
```

**Pygame not found**:
```bash
pip install pygame
```

**Import errors**:
- Ensure all files are in the same directory
- Check Python version compatibility (3.6+)

### Need Help?
- 📧 Open an issue on GitHub
- 📖 Check the existing issues for solutions
- 💬 Contact the maintainers

---

**🎮 Ready to challenge your logic skills? Start playing now!** 

*Made with ❤️ for puzzle enthusiasts everywhere*
