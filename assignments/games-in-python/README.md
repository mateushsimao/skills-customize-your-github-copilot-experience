# 📘 Assignment: Hangman Game Challenge

## 🎯 Objetivo

Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts. This assignment focuses on practicing string manipulation, loops, conditionals, and random selection.

## 📝 Tarefas

### 🛠️ Random Word Selection

#### Description
Write a function to randomly select a word from a predefined list of words.

#### Requirements
Completed program should:

- Contain a predefined list of at least 10 words.
- Randomly select one word from the list.
- Ensure the selected word is hidden from the player initially.

### 🛠️ Letter Guessing Logic

#### Description
Implement the logic to accept letter guesses from the player and update the game state accordingly.

#### Requirements
Completed program should:

- Accept user input for letter guesses.
- Display the current progress of the word in `_ _ _` format.
- Track and display the number of incorrect guesses remaining.
- Validate input to ensure only single letters are accepted.

### 🛠️ Game End Conditions

#### Description
Handle the end-of-game scenarios, including winning and losing conditions.

#### Requirements
Completed program should:

- End the game when the word is fully guessed or the player runs out of attempts.
- Display a win message if the player guesses the word.
- Display a lose message if the player exhausts all attempts without guessing the word.
