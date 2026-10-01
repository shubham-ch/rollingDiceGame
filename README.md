# Rolling Dice Game 🎲

A simple desktop dice-rolling game built with **Python, Tkinter, and Pillow**.

The application provides a graphical interface with two dice. Each time the **"Roll Dices!"** button is clicked, the application randomly generates two dice values and updates the displayed dice images accordingly.

## Overview

This project was created to practice building a simple GUI application in Python and working with:

* Tkinter GUI components
* Image handling with Pillow
* Random number generation
* Python functions
* Lists, tuples, and combinations
* Event-driven programming

## Features

* 🎲 Two virtual dice
* 🖥️ Graphical user interface using Tkinter
* 🔄 Random dice rolls
* 🖼️ Dynamic dice image updates
* 🖱️ Button-based interaction
* 📦 Dice images stored as local assets

## How It Works

The application generates all possible combinations for two six-sided dice:

```text
(1,1), (1,2), ... (1,6)
(2,1), (2,2), ... (2,6)
...
(6,1), (6,2), ... (6,6)
```

A combination is randomly selected whenever the user clicks the **Roll Dices!** button.

The corresponding dice images are then loaded and displayed in the GUI.

## Technology Stack

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| Python     | Application logic                  |
| Tkinter    | Graphical user interface           |
| Pillow     | Loading and displaying dice images |
| itertools  | Generating dice combinations       |
| random     | Selecting random dice results      |

## Project Structure

```text
rollingDiceGame/
│
├── img/
│   ├── 0.jpg
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── 4.jpg
│   ├── 5.jpg
│   └── 6.jpg
│
├── dice.py
│   └── Main application
│
├── .gitignore
│
└── README.md
```

## Requirements

* Python 3.x
* Tkinter
* Pillow

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/shubham-ch/rollingDiceGame.git
cd rollingDiceGame
```

### 2. Install Pillow

```bash
pip install Pillow
```

Tkinter is included with most standard Python installations.

If you are using Linux and Tkinter is not installed, you may need to install it separately through your system package manager.

## Run the Game

Run the Python script:

```bash
python dice.py
```

A desktop window will open with two dice and a **Roll Dices!** button.

Click the button to roll the dice and generate a new random combination.

## Example

The application starts with two dice displayed:

```text
┌───────────────────────────┐
│                           │
│          🎲  🎲           │
│                           │
│                           │
│      [ Roll Dices! ]      │
│                           │
└───────────────────────────┘
```

Each button press generates a new combination of two dice.

## Learning Objectives

This project helped me practice:

* Python GUI development
* Event-driven programming
* Working with external image assets
* Random number generation
* Python collections and iteration
* Integrating third-party libraries
* Structuring a small desktop application

## Author

**Shubham**

GitHub:
https://github.com/shubham-ch

## License

This project is available for educational and personal use.
