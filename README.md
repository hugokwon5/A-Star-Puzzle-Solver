# A* Search N-Puzzle Solver

A high-performance Python implementation of the **A* Search Algorithm** designed to solve the sliding puzzle (8-puzzle, 15-puzzle, and beyond) for grid sizes up to **6x6**.

## Overview
This project explores heuristic-based state-space search. While a standard 3x3 puzzle has a small state space, a 6x6 puzzle presents a significant challenge for search algorithms due to the exponential growth of possible configurations. This solver uses an optimized A* approach to find the shortest path to the goal state.

## Technical Features
* **Algorithm:** A* Search (Informed Search)
* **Heuristic:** Manhattan Distance (Admissible & Consistent)
* **Data Structures:** * `heapq`: Priority Queue for efficient frontier management ($O(\log n)$).
    * `set`: Hash-based visited set for $O(1)$ state lookups.
* **Scalability:** Tested and functional on grids from 3x3 up to 6x6.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/hugokwon5/A-Star-Puzzle-Solver.git](https://github.com/hugokwon5/A-Star-Puzzle-Solver.git)

Run the solver:

   '''bash
   python solver.py
