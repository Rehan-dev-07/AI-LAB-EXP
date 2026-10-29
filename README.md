# 🤖 AI Lab Experiments

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Experiments](https://img.shields.io/badge/Experiments-10-purple)

> A comprehensive collection of **10 Artificial Intelligence Lab Experiments** implemented in Python using Jupyter Notebooks. Each experiment demonstrates a core AI algorithm — from search strategies to game playing to optimization problems.

---

## 📚 Table of Experiments

| # | Experiment | Topic | Algorithm |
|---|------------|-------|-----------|
| 1 | [Iai1.ipynb](Iai1.ipynb) | Breadth First Search | Graph Traversal (BFS) |
| 2 | [Iai2.ipynb](Iai2.ipynb) | Depth First Search | Graph Traversal (DFS) |
| 3 | [Iai3.ipynb](Iai3.ipynb) | Hill Climbing | Local Search / Optimization |
| 4 | [Iai4.ipynb](Iai4.ipynb) | A* Search Algorithm | Heuristic Search |
| 5 | [Iai5.ipynb](Iai5.ipynb) | Minimax Algorithm | Game Tree Search |
| 6 | [Iai6.ipynb](Iai6.ipynb) | Alpha-Beta Pruning | Optimized Game Tree Search |
| 7 | [Iai7.ipynb](Iai7.ipynb) | 8-Queens Problem | Backtracking |
| 8 | [IAI8.ipynb](IAI8.ipynb) | Water Jug Problem | BFS / State Space Search |
| 9 | [IAI9.ipynb](IAI9.ipynb) | Tic-Tac-Toe Game | Rule-Based Game |
| 10 | [Iai10.ipynb](Iai10.ipynb) | Travelling Salesman Problem | Brute Force / Permutations |

---

## 🔍 Experiment Details

### Experiment 1 — Breadth First Search (BFS)
**File:** `Iai1.ipynb`
BFS explores a graph level by level using a **queue**. Guarantees the shortest path in unweighted graphs.
**Input:** Number of vertices, adjacency list, starting vertex.
**Output:** BFS traversal order.

---

### Experiment 2 — Depth First Search (DFS)
**File:** `Iai2.ipynb`
DFS explores as far as possible along each branch before backtracking, using **recursion**.
**Input:** Number of vertices, adjacency list, starting vertex.
**Output:** DFS traversal order.

---

### Experiment 3 — Hill Climbing
**File:** `Iai3.ipynb`
A local search algorithm that continuously moves towards increasing value to find the peak.
**Objective Function:** `f(x) = -(x^2) + 10`
**Input:** Starting value, step size, max iterations.
**Output:** Best position and maximum value found.

---

### Experiment 4 — A* Search Algorithm
**File:** `Iai4.ipynb`
A* combines **actual cost (g)** and **heuristic estimate (h)** to find the optimal path in a weighted graph.
**Input:** Start node and goal node (predefined weighted graph A-G).
**Output:** Shortest path and total cost.

---

### Experiment 5 — Minimax Algorithm
**File:** `Iai5.ipynb`
Decision-making algorithm for **two-player zero-sum games**, alternating between maximizing and minimizing players.
**Input:** 8 leaf node values.
**Output:** Optimal game value.

---

### Experiment 6 — Alpha-Beta Pruning
**File:** `Iai6.ipynb`
Optimizes Minimax by **pruning branches** that cannot affect the final decision, reducing time complexity.
**Input:** 8 leaf node values.
**Output:** Optimal game value (faster than plain Minimax).

---

### Experiment 7 — 8-Queens Problem
**File:** `Iai7.ipynb`
Places 8 queens on an 8x8 chessboard with no two queens threatening each other, solved via **backtracking**.
**Output:** One valid board configuration displayed visually.

---

### Experiment 8 — Water Jug Problem
**File:** `IAI8.ipynb`
Uses **BFS / state space search** to find steps to measure a target water amount using two jugs.
**Input:** Capacities of Jug 1 and Jug 2, target amount.
**Output:** Step-by-step solution path.

---

### Experiment 9 — Tic-Tac-Toe Game
**File:** `IAI9.ipynb`
Two-player **Tic-Tac-Toe** with rule-based win detection. Players X and O alternate on a 3x3 board.
**Output:** Board state after each move, winner or tie announcement.

---

### Experiment 10 — Travelling Salesman Problem (TSP)
**File:** `Iai10.ipynb`
Solves TSP using **brute force permutations** to find the route with minimum total cost.
**Input:** Number of cities, cost matrix, starting city.
**Output:** Best path and minimum travel cost.

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Open any `.ipynb` file on GitHub
2. Click **Open in Colab**
3. Run all cells: `Runtime > Run All`

### Option 2: Local Jupyter Notebook
```bash
git clone https://github.com/<your-username>/AI-Lab-Experiments.git
cd AI-Lab-Experiments
pip install notebook
jupyter notebook
```

### Option 3: VS Code
- Install the **Jupyter** extension
- Open any `.ipynb` file directly

---

## 🛠️ Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab
- No external libraries needed (uses only built-in: `collections`, `math`, `itertools`)

---

## 📂 Repository Structure

```
AI-Lab-Experiments/
├── Iai1.ipynb       # Experiment 1  - BFS
├── Iai2.ipynb       # Experiment 2  - DFS
├── Iai3.ipynb       # Experiment 3  - Hill Climbing
├── Iai4.ipynb       # Experiment 4  - A* Search
├── Iai5.ipynb       # Experiment 5  - Minimax
├── Iai6.ipynb       # Experiment 6  - Alpha-Beta Pruning
├── Iai7.ipynb       # Experiment 7  - 8-Queens Problem
├── IAI8.ipynb       # Experiment 8  - Water Jug Problem
├── IAI9.ipynb       # Experiment 9  - Tic-Tac-Toe
├── Iai10.ipynb      # Experiment 10 - Travelling Salesman
├── .gitignore
└── README.md
```

---

## 🧠 Concepts Covered

| Category | Concepts |
|----------|----------|
| **Search Algorithms** | BFS, DFS, A*, Hill Climbing |
| **Game Theory** | Minimax, Alpha-Beta Pruning, Tic-Tac-Toe |
| **Constraint Satisfaction** | 8-Queens (Backtracking) |
| **State Space Search** | Water Jug Problem |
| **Optimization** | Travelling Salesman Problem, Hill Climbing |

---

## 👤 Author

**Ishaneswar Negi**
**Roll No:** 25CSEAIML282
**Branch:** B.Tech Computer Science (AI & ML)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

⭐ If you found this helpful, give it a **star**!
