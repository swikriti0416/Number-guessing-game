# Number Guessing Game

This Python script implements a simple number guessing game where the user has to guess a randomly generated integer within a specified range.

## Usage

1. Clone this repository to your local machine.
2. Run the script using Python:

    ```bash
    python number_guessing_game.py
    ```

3. Follow the prompts to input the lower and upper bounds of the range and try to guess the randomly generated number within that range.

## How it Works

1. The script prompts the user to enter the lower and upper bounds for the range of numbers within which the random number will be generated.

2. It calculates the maximum number of attempts required to guess the number based on the range using the formula `log2(upper - lower + 1)`.

3. The user then gets multiple attempts to guess the randomly generated number.

4. After each guess, the script provides feedback if the guess is too high, too low, or correct.

5. If the user guesses the number correctly within the allowed number of attempts, they win. Otherwise, the script reveals the correct number.

## Requirements

- Python 3.x

## Credits

This script was created by [swikriti0416](https://github.com/swikriti0416).

Feel free to contribute, report issues, or provide feedback!
