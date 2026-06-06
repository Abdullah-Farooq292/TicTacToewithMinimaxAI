Tic-Tac-Toe with AI (Minimax Algorithm)
A fully functional Tic-Tac-Toe game built with Python, Pygame, and the Minimax algorithm. This project features an unbeatable AI opponent and a clean graphical interface.

-> Features
Human vs. Human or Human vs. AI game modes.

Unbeatable AI: Uses the Minimax decision-making algorithm to ensure the AI never loses.

Game Difficulty Levels: Switch between "Random" (Level 0) and "Impossible" (Level 1) AI.

Interactive UI: Responsive board drawing using Pygame.

Game Control Shortcuts: Easily reset the game, toggle modes, or change difficulty during play.

-> Prerequisites
Ensure you have Python installed, then install the necessary dependencies:

pip install pygame numpy

-> How to Play
Run the game:
python main.py

Controls:

Click on any empty square to place your mark.

g: Toggle between PvP (Player vs Player) and PvE (Player vs AI) modes.

r: Restart the game.

0: Set AI difficulty to Random.

1: Set AI difficulty to Impossible (Minimax).

-> How the AI Works (Minimax)
The "Impossible" AI uses the Minimax algorithm, a recursive decision-making strategy used in game theory.

Recursion: The AI simulates every possible future state of the board by recursively playing out all possible moves.

Scoring: It assigns a value to each final state:

+1 if the human wins.

-1 if the AI wins.

0 for a draw.

Decision: The AI then chooses the path that minimizes the potential score (assuming the AI is the minimizing player).

-> Project Structure
main.py: The entry point and main game loop.

constants.py: Holds configuration settings (colors, dimensions, board size).

-> License
This project is open-source and free to use for learning purposes. Enjoy playing and feel free to extend the code!

