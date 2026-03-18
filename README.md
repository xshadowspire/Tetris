# Tetris
This project is a classic Tetris clone developed in Python. It features a complete implementation of the game's core mechanics, including piece generation, grid management, and line-clearing algorithms. The project highlights efficient use of data structures (matrices) and real-time event handling.
Technical Features
Grid System: Uses a 2D matrix to track the state of the 10x20 game board.
Tetromino Logic: All 7 standard shapes are implemented with their respective rotation states.
Collision Detection: Algorithms ensure pieces stay within boundaries and do not overlap.
Line Clearing: Automatically identifies full rows, removes them, and shifts the remaining blocks down.
Score Tracking: Points are awarded based on the number of lines cleared.
How to Run
Ensure you have Python 3.x installed.
Install the required library (Pygame): pip install pygame.
Run the game: python tetris.py.
