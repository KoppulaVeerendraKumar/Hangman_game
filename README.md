# Hangman Game

## Overview
This is a **Python Hangman Game** where the player must guess a randomly selected animal name. The player has **6 chances** to guess the correct word before the Hangman is fully drawn.

## How to Play
1. Run the script in a Python environment.
2. The game will display the word as underscores (`_ _ _`) where each underscore represents a letter.
3. The player guesses letters one at a time.
4. If the letter is in the word, it is revealed in its correct position.
5. If the letter is incorrect, a part of the Hangman is drawn, and the number of remaining attempts decreases.
6. The game continues until the player either **guesses the word correctly (wins)** or **runs out of attempts (loses).**

## Features
- Random word selection from a predefined list of animals.
- Tracks correctly and incorrectly guessed letters.
- Displays a visual Hangman progression.
- User-friendly messages for guidance.




## Code Explanation
- The game randomly selects an animal name from a predefined list.
- The player guesses letters, and correct guesses are revealed in the word.
- Incorrect guesses result in a Hangman figure being drawn step by step.
- The game ends when the player either completes the word or uses up all attempts.

## Example Output
```
Guess the word:  _ _ _ _ _
6 chances left
> a
Sorry! You have guessed a wrong letter!
+---+
    |
    |
    |
    ===

Guess the word:  _ _ _ _ _
5 chances left
> t
Awesome Job! You guessed the correct letter!
```



