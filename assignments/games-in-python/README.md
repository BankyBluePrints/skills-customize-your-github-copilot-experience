
# 📘 Assignment: Games in Python - Hangman

## 🎯 Objective

Build a console Hangman game that selects a random word and lets players guess letters with limited attempts while showing progress and win/lose outcomes.

## 📝 Tasks

### 🛠️ Core Hangman Game

#### Description
Implement the base game loop: choose a word, process guesses, track attempts, and determine win or loss.

#### Requirements
Completed program should:

- Choose a random word from a predefined list at startup.
- Show masked word progress (e.g., `_ _ n _ _`) and remaining attempts after each guess.
- Detect game end states and display clear win or lose messages.


### 🛠️ User Experience Enhancements

#### Description
Add polish so the game feels friendly and robust for players.

#### Requirements
Completed program should:

- Validate input to accept only single letters and ignore repeats without consuming attempts.
- Track and display guessed letters (correct and incorrect) each turn.
- Offer an option to play again without restarting the script.
