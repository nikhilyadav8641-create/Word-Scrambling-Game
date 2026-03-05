
# Word Scrambling Game (Python)

## Description
This is a simple command line Word Scrambling Game written in Python.  
The program randomly selects a word from a list and scrambles its letters.  
The player has to guess the correct word from the scrambled version.

The player gets **3 attempts** to guess the correct word.  
If the guess is correct, the player earns **10 points**.

The game continues until the player chooses to stop.

---

## Features
- Random word selection
- Scrambled word display
- 3 attempts for each word
- Score tracking
- Option to play again
- Simple command line interface

---

## Technologies Used
- Python 3
- Random module

---

## How the Game Works
1. The program selects a random word from a predefined list.
2. The word is scrambled using the `random.shuffle()` function.
3. The scrambled word is displayed to the player.
4. The player gets **3 chances** to guess the correct word.
5. If the guess is correct:
   - The player gets **10 points**.
6. If the player fails all attempts:
   - The correct word is displayed.
7. The player is asked whether they want to play again:
   - Enter **1** → Continue playing
   - Enter **0** → Exit the game.

---

## How to Run the Program

1. Make sure Python is installed on your system.
2. Save the program as `game.py`.
3. Open terminal or command prompt.
4. Run the program using:
