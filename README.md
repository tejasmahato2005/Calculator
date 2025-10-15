# Calculator

A simple yet elegant calculator application built with Python and tkinter. Perform basic arithmetic operations with an intuitive graphical interface.

## Features

- ✅ Basic arithmetic operations (addition, subtraction, multiplication, division)
- ✅ Clean, modern graphical user interface
- ✅ Clear button to reset calculations
- ✅ Real-time display of expressions
- ✅ Error handling for invalid operations
- ✅ Keyboard support for input
- ✅ Cross-platform compatible (Windows, Mac, Linux)

## Requirements

- Python 3.6 or higher
- tkinter (comes built-in with Python)

## Preview

## Preview

![Calculator Application](calculator.png)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/calculator.git
cd calculator
```

### 2. Verify Python Installation
```bash
python --version
```

### 3. Run the Calculator
```bash
python calculator.py
```

## Usage

### Basic Operations

1. **Addition**: Click numbers and `+` button, then `=`
   - Example: `5 + 3 =` displays `8`

2. **Subtraction**: Use `-` button for subtraction
   - Example: `10 - 4 =` displays `6`

3. **Multiplication**: Use `*` button for multiplication
   - Example: `6 * 7 =` displays `42`

4. **Division**: Use `/` button for division
   - Example: `20 / 4 =` displays `5`

5. **Clear**: Click `clear` button to reset and start over

### Keyboard Shortcuts
```
Numbers:  0-9
Operators: + - * /
Enter:     Press = or Enter key
Clear:     Press C or Delete key
```

## File Structure

```
calculator/
├── calculator.py          # Main application file
├── README.md             # This file
└── requirements.txt      # Python dependencies (if any)
```

## Code Example

```python
# Basic usage structure
from calculator import Calculator

calc = Calculator()
calc.run()
```

## Features Breakdown

### Number Buttons (0-9)
- Click to input numbers into the display
- Supports multiple digit numbers

### Operation Buttons (+, -, *, /)
- Select the operation to perform
- Display updates as you build the expression

### Equals Button (=)
- Calculates the result of the current expression
- Displays the answer

### Clear Button
- Resets the calculator
- Clears display and history
- Ready for new calculation

## Example Calculations

| Expression | Result |
|-----------|--------|
| 10 + 5    | 15     |
| 20 - 8    | 12     |
| 6 * 7     | 42     |
| 100 / 4   | 25     |
| 3 + 4 * 2 | 11     |

## Troubleshooting

### "Module tkinter not found"
- **Windows**: Usually comes with Python. Reinstall Python with tkinter option checked.
- **Mac**: Install Python from python.org or use Homebrew: `brew install python-tk`
- **Linux**: Run `sudo apt-get install python3-tk`

### Calculator window won't open
- Make sure you're using Python 3.6+
- Try running: `python3 calculator.py` instead of `python calculator.py`

### Can't type numbers
- Make sure the calculator window has focus (click on it)
- Try clicking number buttons with mouse

## Limitations

- Supports basic arithmetic operations only
- No scientific functions (sin, cos, log, etc.)
- No memory functions (M+, M-, MR, MC)
- Single expression at a time

## Future Enhancements

- [ ] Add scientific calculator mode
- [ ] Add calculation history
- [ ] Add keyboard numpad support
- [ ] Add themes/dark mode
- [ ] Add memory functions
- [ ] Add decimal point support

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Author

Your Name - [Your GitHub](https://github.com/tejasmahato2005)

## Support

If you encounter any issues, please:
1. Check the Troubleshooting section
2. Open an issue on GitHub
3. Contact the maintainer

## Acknowledgments

- Built with Python and tkinter
- Inspired by classic calculator designs
- Thanks to all contributors!
