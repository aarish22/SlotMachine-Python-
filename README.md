# 🎰 Slot Machine Game

## About the Project

This project is a text-based slot machine game implemented in Python. Players can deposit money, place bets on multiple lines, spin the slot machine, and potentially win money based on the outcome of the spin.

## Features

- **Deposit Money**: Players can deposit money to start playing.
- **Place Bets**: Players can bet on up to three lines with customizable bet amounts within a specified range.
- **Slot Machine Spin**: Simulates a slot machine spin with random symbols.
- **Winnings Calculation**: Calculates winnings based on the matched symbols and updates the player's balance.
- **User-Friendly Interface**: Simple text-based interface for easy interaction.

## Technologies Used

- **Python**: The programming language used for the project.

## How It Works

1. **Deposit Money**: Players are prompted to deposit money to start the game.
2. **Place Bets**: Players choose the number of lines to bet on and the amount to bet per line.
3. **Spin the Slot Machine**: The slot machine spins and displays the outcome.
4. **Calculate Winnings**: The game calculates and displays the player's winnings based on the symbols and the bet.
5. **Update Balance**: The player's balance is updated, and they can choose to spin again or quit the game.

## Game Rules

- **Symbols**:
  - `A`: Appears 2 times, value 5
  - `B`: Appears 4 times, value 4
  - `C`: Appears 6 times, value 3
  - `D`: Appears 8 times, value 2
- **Winning Lines**: The game checks for matching symbols across the specified lines to determine winnings.

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/slot-machine-game.git
    cd slot-machine-game
    ```

2. **Run the Script**:
    ```bash
    python slot_machine.py
    ```

3. **Follow the Prompts**:
    - Enter the amount to deposit.
    - Enter the number of lines to bet on.
    - Enter the bet amount per line.
    - Spin the slot machine and see the results.
    - Continue playing or quit the game.

## Example

```plaintext
What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 3
What would you like to bet on each line? $5
You are betting $5 on 3 lines. Total bet is equal to: $15
A | B | A
D | D | D
B | C | C
You won $0.
You won on lines:
Current balance is $85
Press enter to play (q to quit).
