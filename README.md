# Maze Solver

This Python program solves a maze specified in a text file using various search algorithms.

## Features

- **Maze Solving**: Finds the solution to a maze represented in a text file.
- **Visualization**: Generates an image of the maze with the solution path highlighted.
- **Multiple Algorithms**: Supports different search algorithms for finding the solution.
- **Efficient Frontier Handling**: Uses priority queue-based frontier for efficient exploration.
- **Easy to Use**: Simple command-line interface for specifying the maze file and displaying the solution.

## Usage

To use the maze solver:

1. Clone the repository or download the Python script.
2. Ensure you have Python installed on your system.
3. Run the script using the following command: <h3>python maze.py maze.txt</h3>
Replace `maze.txt` with the path to your maze file.

## File Format

The maze should be represented in a text file where:
- 'A' represents the starting point.
- 'B' represents the goal.
- '#' represents walls.
- ' ' (space) represents open space or paths.

## Algorithms

The solver supports the following search algorithms:
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- A* Search


## Dependencies

- Python 3.x
- PIL (Python Imaging Library) for image generation
