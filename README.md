# Ultimate Tic Tac Toe
<img width="724" height="749" alt="Screenshot 2025-09-09 at 5 30 27 PM" src="https://github.com/user-attachments/assets/9d547a3d-c8c1-46dd-91c6-172b1933c8af" />
<img width="718" height="723" alt="Screenshot 2025-09-09 at 5 54 23 PM" src="https://github.com/user-attachments/assets/1261722d-4937-4e92-955c-1a22299c870b" />

## Overview
Ultimate Tic Tac Toe is an advanced version of the classic Tic Tac Toe game. It features a large 9x9 grid composed of 81 smaller boxes grouped into 81 large boxes, each containing a traditional 3x3 Tic Tac Toe board. Players play on the small boards, and winning them strategically determines the overall winner.

## Features
- Interactive graphical interface using Pygame
- Nested board structure: 9 large boards, each containing a 3x3 small board
- Rules enforcement for Ultimate Tic Tac Toe gameplay
- Designed with modular Python classes for scalability and clarity

## How to Run
1. Make sure you have Python 3.x installed.
2. Install required modules:
3. Run the game:


## Project Structure
- `main.py`: Entry point that starts the game window and main loop
- `const.py`: Constants such as board size and colors
- `board.py`: Logic and representation of the game board and large boxes
- `board_dim.py`: Handles dimensions and coordinates of the boards
- `game.py`: Main game mechanics, rules, and player interaction

## How the Game Works
- The 9x9 grid is split into 81 large boxes.
- Each large box contains a mini 3x3 Tic Tac Toe board.
- Players take turns playing in the smaller boxes.
- Winning a small board means claiming that large box.
- The objective is to win three large boxes in a row to win the game.

## Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License.

---
Enjoy strategic Tic Tac Toe like never before!
