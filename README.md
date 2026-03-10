# Connect 4 Game (Python)

A simple **Connect 4 game built using Python**. This is a terminal-based implementation where two players take turns dropping discs into a grid. The goal is to connect four discs in a row horizontally, vertically, or diagonally.

## Features

* Two-player gameplay
* 6x7 game board
* Win detection (horizontal, vertical, diagonal)
* Tie detection
* Simple command-line interface
* Beginner-friendly Python code

## How the Game Works

1. The board consists of **6 rows and 7 columns**.
2. Players take turns choosing a column (1–7).
3. The disc automatically falls to the **lowest empty position** in that column.
4. The first player to connect **four discs in a row** wins.
5. If the board fills up with no winner, the game ends in a **tie**.

## Board Example

```
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
|X|O|X|O|X|O|X|
 1 2 3 4 5 6 7
```

## Requirements

* Python 3.x

## Future Improvements

* Add **computer AI opponent**
* Create a **graphical interface using Tkinter or Pygame**
* Add **score tracking**
* Improve input validation

## Learning Goals

This project helps practice:

* Python loops and conditionals
* Lists and 2D arrays
* Game logic implementation
* Problem solving

## Author

Created as a Python practice project for learning game development and logic building.
