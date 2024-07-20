# Shortest_path_finder_python
This is a Pyhton project to find shortest path

You need to install curses package == pip install curses

The code uses Breadth-First Search (BFS) algorithm to find the shortest path in a maze. Here's how it works:

Initialization:

The maze is defined as a 2D list.
The starting position ('O') and ending position ('X') are identified.
A queue is used to manage the positions to be explored, and a set keeps track of visited positions.
BFS Execution:

The starting position is added to the queue.
The algorithm enters a loop where it dequeues the front position, marks it as visited, and explores its neighbors.
Each neighbor is checked to see if it is the end position ('X'). If it is, the path is returned.
If a neighbor is not a wall ('#') and hasn't been visited, it is added to the queue for further exploration.

Visualization:

The current state of the maze and the path taken is printed on the screen at each step using the curses library.
The visualization shows the process of the algorithm finding the path through the maze.
By using a queue to explore each level of the maze fully before moving on to the next, BFS guarantees that the shortest path to the end will be found.

