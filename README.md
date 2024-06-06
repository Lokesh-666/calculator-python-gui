# My Calculator

A simple GUI-based calculator application built with Python and Tkinter. This calculator supports basic arithmetic operations and includes additional navigation functions.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, division
- Clear button to reset the input
- Navigation buttons for moving the cursor within the entry field
- User-friendly GUI built with Tkinter

## Requirements

Before running the calculator, ensure you have the following installed on your system:

- Python 3.x: [Download and install Python](https://www.python.org/downloads/)
- Tkinter: Tkinter comes pre-installed with Python. However, if it's not available, you can install it via pip:
  ```sh
  pip install tk
  ```
- `pyautogui` library for navigation buttons:
  ```sh
  pip install pyautogui
  ```
- `simple-calculator` library for arithmetic operations:
  ```sh
  pip install simplecalculator
  ```

## How to Use

1. Clone the repository or download the source code.

   ```sh
   git clone https://github.com/Lokesh-666/calculator-python-gui.git
   cd calculator-python-gui
   ```

2. Ensure all the requirements are installed (see the Requirements section).

3. Run the calculator:

   ```sh
   python calculator.py
   ```

4. The calculator window will open. You can use the buttons on the GUI to perform arithmetic operations and other actions.

## Code Overview

The main script `calculator.py` initializes a Tkinter window and sets up the calculator interface. Here is a brief overview of the code:

- `AddNewClick(click)`: Adds the clicked button's value to the entry field.
- `ClearTheScreen()`: Clears the entry field.
- `CalculateIt()`: Evaluates the expression in the entry field using the `simple-calculator` library and displays the result.
- `Actions(Action)`: Handles additional actions like clearing the entry field and moving the cursor left or right.

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are welcome.

## License

This project is open source and available under the [MIT License](LICENSE).

---
