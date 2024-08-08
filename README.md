# Hangman Word Game

## Overview

This project is a Python implementation of the classic word-guessing game **Hangman**. The game randomly selects a word, and the player attempts to guess the word by suggesting letters within a limited number of attempts. This project was inspired by the online version of [Hangman Word Game](https://hangmanwordgame.com/).

## Features

- **Random Word Selection:** The game chooses a word from a predefined list of challenging words.
- **Player Feedback:** Displays the current progress of the word with correctly guessed letters.
- **Lives System:** Players have a limited number of lives (6) to guess the word.
- **Graphical Feedback:** ASCII art is used to represent the hangman’s state as the player loses lives.
- **Replayability:** The word list includes a variety of words, allowing for multiple rounds of gameplay.

## Project Structure

The project is organized as follows:

```plaintext
hangman/
│
├── hangman.py         # Main game logic
├── hangman_words.py   # Contains the list of words
├── hangman_art.py     # Contains ASCII art and logo
├── README.md          # Project documentation
└── .gitignore         # Files to ignore in version control
