# AI-class

This repository contains a collection of projects and algorithms developed as part of an Artificial Intelligence (AI) course. The focus spans multiple AI paradigms, including **search algorithms**, **constraint satisfaction problems**, and **game-playing strategies**, implemented across multiple programming languages (Java, C#, Python).

---

## 📁 Repository Structure

### 1. `CSP-Graph-Colouring/`

- **Language:** Java
- **Description:** This directory contains an implementation of the **Graph Colouring problem** modeled as a **Constraint Satisfaction Problem (CSP)**. The goal is to assign colours to the vertices of a graph such that no two adjacent vertices share the same colour, while using the minimum number of colours possible.
- **Highlights:**
  - Representation of graphs using adjacency structures.
  - Backtracking search with constraint propagation (e.g., forward checking).
  - Heuristics such as Minimum Remaining Values (MRV) and Degree Heuristic.

### 2. `MiniMax_Tic_Tac_Toe/`

- **Language:** C#
- **Description:** Demonstrates the **Minimax algorithm** in a classic **Tic-Tac-Toe** game setting. The uploaded files include the core game logic and AI decision-making code.
- **Note:** Although the application was designed with a GUI, only the core `.cs` files are included in the repository. These files are sufficient to understand the AI logic behind move selection and game-tree traversal.
- **Highlights:**
  - Minimax algorithm with depth-based evaluation.
  - Game state representation and move generation.
  - Turn-based logic and endgame evaluation.

### 3. Standalone Python Scripts

These scripts cover fundamental **search algorithms** and **local search methods**, commonly taught in AI courses:

| File Name                          | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| `best_first_search.py`            | Implements the **Best-First Search** strategy using a heuristic function.  |
| `breadth_first_search.py`         | Standard **Breadth-First Search (BFS)** implementation using a FIFO queue. |
| `depth_first_search.py`           | Implements **Depth-First Search (DFS)** using a LIFO stack.                |
| `priority_queue.py`               | A custom **priority queue** class used in `best_first_search.py`.         |
| `queue.py`                        | Contains `FIFOQueue` and `LIFOQueue` classes used for BFS and DFS.        |
| `min_conflicts_ls_8queens.py`     | Solves the **8-Queens problem** using **Min-Conflicts**, a local search heuristic. |
| `simulated_annealing_8queens.py` | Solves the **8-Queens problem** using **Simulated Annealing**.            |

---

## 🧠 Algorithms Overview

### Search Techniques
- **Breadth-First Search (BFS):** Explores all nodes at the current depth before moving to the next level.
- **Depth-First Search (DFS):** Explores as far as possible along a branch before backtracking.
- **Best-First Search:** Uses a priority queue based on a heuristic evaluation of node desirability.

### Local Search
- **Min-Conflicts (8 Queens):** A heuristic repair method that starts with a complete assignment and iteratively minimizes constraint violations.
- **Simulated Annealing (8 Queens):** A probabilistic technique to approximate the global optimum of a function in a large search space.

---

## 🚀 Getting Started

Clone the repository:
```bash
git clone https://github.com/your-username/AI-class.git
cd AI-class
