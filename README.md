# Conways-Game-of-Life

README file for Conway's Game of Life

Introduction:
Conway's Game of Life is a cellular automaton simulation that was invented by John Horton Conway in 1970. It is a zero-player game, which means that its evolution is determined by its initial state and does not require any further input. The game is played on a grid of cells, where each cell can either be alive or dead. The game is based on a set of rules that dictate how the cells evolve over time. These rules are very simple, yet they can produce incredibly complex patterns.

Installation:
To run this implementation of the game, you need to have Python 3, Numpy, Time and Pygame installed on your system. You can install Python from https://www.python.org/downloads/ and Pygame can be installed by running the command "pip install pygame", "pip install time", "pip install numpy" in the terminal.

Running the game:
To run the game, open a terminal or command prompt and navigate to the directory where the implementation is saved. Then, type "python game_of_life.py" and press enter. The game will start and you will see an empty grid with a black background. You can start adding cells by clicking on the cells with your left mouse button. You can also pause and resume the game by pressing the spacebar.

Rules:
The rules of the game are very simple:
1. Any live cell with fewer than two live neighbors dies, as if by underpopulation.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

Implementation:
This implementation uses Pygame to create the graphical interface and to handle the mouse and keyboard inputs. The game grid is represented using a two-dimensional numpy array, where each element can be either 0 or 1. The update function calculates the next state of the cells based on the rules of the game and returns a new numpy array that represents the updated grid. The main loop of the game updates the grid and displays it on the screen. The user can interact with the game by clicking on the cells with the left mouse button and by pausing and resuming the game with the spacebar.

Conclusion:
Conway's Game of Life is a fascinating simulation that demonstrates how simple rules can lead to complex patterns and behavior. This implementation provides a simple way to explore the game and to experiment with different initial states and configurations.
