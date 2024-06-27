# tictactoe-using-alpha-beta-prunning-and-MCTS

#Tic-Tac-Toe AI Project
This project is an implementation of the classic Tic-Tac-Toe game with advanced AI algorithms. The AI uses both Minimax with Alpha-Beta Pruning and Monte Carlo Tree Search (MCTS) to play against human players or simulate games between two AI opponents.

##Features
###Two Game Modes:

Human vs Computer
Computer vs Computer
###AI Algorithms:

Minimax with Alpha-Beta Pruning
Monte Carlo Tree Search (MCTS)

#Project Structure
tic_tac_toe.py: Main script to run the game.
minimax.py: Contains the Minimax algorithm with Alpha-Beta Pruning.
mcts.py: Contains the Monte Carlo Tree Search algorithm.
game_utils.py: Contains utility functions for the game, including board setup, move validation, and game state evaluation.

#How to Play
###Human vs Computer
Run the script.
Choose the game mode by entering 1 for Human vs Computer.
Enter 1 to play first or 2 to play second.
Make your move by entering a number between 1-9 corresponding to the board positions:

1 | 2 | 3
-----------
4 | 5 | 6
-----------
7 | 8 | 9


###Computer vs Computer
Run the script.
Choose the game mode by entering 2 for Computer vs Computer.
Watch as the two AI players compete against each other.

#Minimax with Alpha-Beta Pruning
The Minimax algorithm is used to find the optimal move for the AI by simulating all possible moves and their outcomes. Alpha-Beta Pruning is applied to reduce the number of nodes evaluated by the Minimax algorithm, making it more efficient.

#Monte Carlo Tree Search (MCTS)
MCTS is a heuristic search algorithm used to make optimal decisions in game theory. It uses random sampling of the search space to build a search tree and evaluate the potential moves based on their outcomes.

#Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.
