# Hangman Game

![C Logo](https://upload.wikimedia.org/wikipedia/commons/1/19/C_Logo.png)

Welcome to the Hangman Game! This is a simple command-line game implemented in C. Enjoy guessing the words and have fun!

## Rules

1. The game will randomly select a word.
2. You have to guess the word letter by letter.
3. You have a limited number of attempts to guess the word.
4. Each incorrect guess will reduce the number of attempts left.
5. The game ends when you either guess the word correctly or run out of attempts.

## Functions

- **Word Selection**: Randomly selects a word from a predefined list.
- **Input Handling**: Takes user input for guessing letters.
- **Display**: Shows the current state of the word with guessed letters and remaining attempts.
- **Win/Lose Conditions**: Checks if the player has won or lost the game.

## Audio

The game includes audio feedback for correct and incorrect guesses. Make sure your device's audio is enabled to enjoy this feature.

## Features

- Random word selection
- Limited attempts for guessing
- Audio feedback for guesses
- Command-line interface

## How to Play

1. Open the terminal in Visual Studio Code.
2. Compile the game using the following command:
   ```sh
   gcc game1.c -o game1 -lwinmm

3. ### [README.md](file:///c%3A/Users/qures/projects/c-project/hangman/README.md)

```markdown
# Hangman Game

Welcome to the Hangman Game! This is a simple command-line game implemented in C. Enjoy guessing the words and have fun!

## Rules

1. The game will randomly select a word.
2. You have to guess the word letter by letter.
3. You have a limited number of attempts to guess the word.
4. Each incorrect guess will reduce the number of attempts left.
5. The game ends when you either guess the word correctly or run out of attempts.

## Functions

- **Word Selection**: Randomly selects a word from a predefined list.
- **Input Handling**: Takes user input for guessing letters.
- **Display**: Shows the current state of the word with guessed letters and remaining attempts.
- **Win/Lose Conditions**: Checks if the player has won or lost the game.

## Audio

The game includes audio feedback for correct and incorrect guesses. Make sure your device's audio is enabled to enjoy this feature.

## Features

- Random word selection
- Limited attempts for guessing
- Audio feedback for guesses
- Command-line interface

## How to Play

1. Open the terminal in Visual Studio Code.
2. Compile the game using the following command:
   ```sh
   gcc game1.c -o game1 -lwinmm
   ```
3. Run the game using the following command:
   ```sh
   ./game1
   ```

## Setting Up the Environment

To run the C code on your device, you need to install the MinGW compiler. Follow the instructions below to set up MinGW:

1. Download MinGW from the official website: [MinGW Download](https://sourceforge.net/projects/mingw/)
2. Install MinGW and add it to your system's PATH environment variable.
3. Verify the installation by running `gcc --version` in the terminal.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Enjoy playing the Hangman Game!
```
