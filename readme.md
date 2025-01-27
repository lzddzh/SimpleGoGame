# Simple Go Game

## Overview
This is a web-based implementation of the classic board game Go. The game allows players to compete against each other or against a basic computer opponent. It features customizable board sizes, score tracking, and support for simple rules including suicide and capturing.

## Features
- Play modes:
  - Human vs. Human
  - Human vs. Computer (random moves)
- Customizable board sizes (19x19, 13x13, etc.)
- Komi support for balancing the game
- Move tracking and undo functionality
- Automatic scoring using a simplified Chinese-style system
- Board coordinates display for easy navigation
- Last move highlighting with a circle marker

## How to Play
1. Choose your preferred board size and game mode.
2. Set the Komi (handicap points for White).
3. Click "Start New Game" to begin.
4. For Human vs. Computer, select your color (Black or White).
5. Place stones by clicking on the board.
6. Track scores and captures in real-time.
7. Click "Undo" to revert the last move if needed.

## Scoring System
We use a simplified **Chinese-style** scoring approach:

- **Points = Territory + Stones on Board + Komi (for White)**
- Territory is estimated by counting empty areas fully enclosed by one color.
- Capturing removes an opponent’s stones from the board, reducing their final total.
- Komi is set to **0 by default**, but you can change it to balance the game.

**No advanced rules:** No Ko ban, no seki detection, and **Undo** only removes the last placed stone (it doesn’t restore captured stones).

## Screenshot
![Simple Go Game Screenshot](link_to_screenshot.png)  <!-- Replace with actual link -->

## How to Run
1. Download or clone this repository.
2. Open `simple_go_game.html` in a web browser. (Only Chrome being tested)
3. Enjoy playing Go!

## Credits
This project was primarily developed using OpenAI's ChatGPT-o1, with additional debugging and prompt engineering by **Stark**, the author of this web game.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

