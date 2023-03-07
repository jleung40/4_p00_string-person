# Project 00 For NeXT CS
### Class Period:
### Name0: Jasper
---


Your mission is to recreate one of these three games that involve working with strings:
- [Wordle](https://wordplay.com/new)
- [Spelling Bee](https://spellingbeegame.org)
- [Type Racer](https://play.typeracer.com)

This project will be completed in phases. The first phase will be to work on this document. Use makrdown formatting. For more markdown help [click here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

All projects will require the following:
- A visual interface representative of the game. The entirety of the game should run in a window, not via the Processing console.
- Reading in text from a plain text file.
  - I will provide useful text files for the various games.
- The ability for users to start a new game without having to restart the program (either resetting after completing a round of the game, or allowing users to reset in the middle of a current game).
- Allowing text input via the keyboard.
- Some form of score/point system that is maintained while the program is running. (It does not need to keep track of score after the fact).

Wordle Specific Requirements:
- Gameplay should follow Wordle rules. The coloring of the squares should work the same way it does for Wordle (play a few rounds to understand th specifics surrounding duplicate letters).

Spelling Bee specific requirements:
- Users should be able to see the words they have already entered.

Type Racer specific requirements.
- There should be a visual indication of how are along the user is (similar to the cars in type racer).
- This should only be a 1-player game, even if you add other features.


---

## Phase 0: Game Selection, Analysis & Plan

#### Selected Game: Wordle

### Rules
What are the core rules of your game?

Guess the word correcty 7 chances with hints.

### Necessary Features
What are the core features that your game should have? These should be things that __must__ be implemented in order to make the game playable, not extra features that could be added to make the game more fun to play.

Correct letters in wrong placement would be colored yellow and correct letters in the correct placement would be green and all others would be red.

### Extra Features
What are some features that are not essential to gameplay, but you would like to see (provided you have time after completing the necessary features.

Harder words as you get more words correct.(random words from the guess file)

#### Interface
What will your game look like?

A rectangle of letters the word(s)(length) by 7 boxes(height). With a additional row on the top for extra controls(like restart) and information(like words correct) and a space on the bottom with a keyboard to make it easier to know which letters not to use.

### Controls
How will your game be controlled?

Keyboard Controls:
All letters of the keyboard for writing the words.
Enter to submit guesses.
Backspace for erasing letters

Mouse Controls:
Left click on restart to restart the game and change the word to another random word.


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes.

CLASS NAME0: Word
- Instance variables:
  - Char letters
- METHODS
  - array for the letters

CLASS NAME1: Boxes
- Instance variables:
  - int length
  - int width
- METHODS
  - 2D Array for boxes

CLASS NAME2: Keyboard
- Instance variables:
  - Int Length
  - Int width
- METHODS
  - 2D array for the keyboard(going to be rectangular and not look like a keyboard)
