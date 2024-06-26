# Python Slot Machine Game

A simple Python-based slot machine game where players can deposit money, place bets, and spin the slot machine to potentially win more money. This project demonstrates basic concepts of Python programming such as loops, functions, and user input handling.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Example Playthrough](#example-playthrough)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Features
- Players can deposit money and place bets on up to three lines.
- The slot machine features a 3x3 grid with four different symbols (A, B, C, D), each with different winning values.
- Dynamic betting system where winnings are calculated based on the symbol and bet amount.
- Simple and interactive command-line interface.

## Installation

### Prerequisites
- Python 3.x must be installed on your system.

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/python-slot-machine.git
    ```
2. Navigate to the project directory:
    ```bash
    cd python-slot-machine
    ```

No additional dependencies are required as this project uses only the Python Standard Library.

## Usage

To start the game, run the `main.py` script:

```bash
python main.py


How to Play
Deposit: Start by depositing an amount of money to play with.
Betting: Choose the number of lines (1 to 3) you want to bet on and the amount to bet per line.
Spin: Spin the slot machine and see if you've won based on the displayed symbols.
Winnings: Your winnings will be added to your balance, and you can continue playing or quit the game.
Game Rules
Symbols and Counts:
'A': 2 occurrences
'B': 4 occurrences
'C': 6 occurrences
'D': 8 occurrences
Symbol Values:
'A': 5x the bet
'B': 4x the bet
'C': 3x the bet
'D': 2x the bet
Winning Conditions: A line wins if all three symbols in that line are the same.
Maximum Lines: You can bet on up to 3 lines.
Bet Limits: Minimum bet is $1 and the maximum bet is $100 per line.
