# A* Search Algorithm Maze Solver
This project implements the A* search algorithm to find the shortest path in a randomly generated maze. The maze is represented as a 2D grid, where 0 denotes an empty cell and 1 denotes an obstacle. The algorithm uses the Manhattan distance heuristic to guide the search.

## Features
- Random maze generation with adjustable obstacle probability.
- A* search algorithm implementation.
- Visualization of the maze, start and goal points, and the shortest path using matplotlib.
  
## Implementation Details
- The A* algorithm is implemented in the astar function.
- Heuristic function uses the Manhattan distance.
- The program outputs the shortest path or notifies if no path is found.

## Prerequisites
- Python 3.x
- matplotlib library ('pip install matplotlib')
