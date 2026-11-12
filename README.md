# 3D A* Pathfinding and Maze Generation

A Python project that demonstrates A* pathfinding in three-dimensional space and visualizes the resulting route through obstacles and generated mazes.

## Project overview

The project represents a 3D environment as a grid. A* searches from a starting coordinate to a target coordinate while avoiding blocked cells. Parent tracking reconstructs the final route, and Matplotlib displays the path and obstacles in three dimensions. The notebook also explores randomized 3D maze generation.

## Concepts demonstrated

- A* graph search
- Euclidean-distance heuristic
- Priority queues with heapq
- Node cost and parent tracking
- Path reconstruction
- Boundary and collision checks
- Randomized maze generation
- NumPy grid structures
- Matplotlib 3D visualization

## Notebook

[Open the original notebook in Google Colab](https://colab.research.google.com/drive/1Ryd1y1JBPNJR3P3LY9S6_7VgoSys_j-j)

## Technology

Python, NumPy, Matplotlib, heapq, and standard Python data structures.

## Current status

The academic notebook is being reorganized into reusable modules. Planned improvements include automated tests, configurable maze dimensions, reproducible random seeds, path-cost reporting, and an animated visualization.
