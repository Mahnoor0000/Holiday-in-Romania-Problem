

# Holiday in Romania – Search Algorithms

This repository implements the classic **Holiday in Romania** problem from *Artificial Intelligence: A Modern Approach (AIMA)*, solved using three informed search strategies:

- **Uniform Cost Search (UCS)** – expands nodes in order of path cost `g(n)`, always finds the optimal path.
- **Greedy Best-First Search (GBFS)** – expands nodes in order of heuristic `h(n)` (straight-line distance to Bucharest), fast but not always optimal.
- **A\*** – expands nodes in order of `f(n) = g(n) + h(n)`, combining UCS and GBFS. Optimal and efficient with an admissible heuristic.

The algorithms are applied to the Romania map problem (finding a route from **Arad** to **Bucharest**).

---

## Features
- Graph representation of Romania with distances between cities
- Straight-line distance heuristic table (from each city to Bucharest)
- Implementations of:
  - Uniform Cost Search
  - Greedy Best-First Search
  - A\* Search
- Path reconstruction showing:
  - Optimal path
  - Total path cost
  - Number of expanded nodes
  - Node expansion order

---

## Example Output
