# Overview of Search Algorithms in Graphs

## Depth-First Search (DFS)
- **Principle**: Utilizes a stack (either actual or through recursion) for search operations.
- **Process**: Starts at a node, explores as deep as possible along each branch before backtracking.
- **Application**: Suitable for tasks like puzzle solving, topological sorting, and exploring paths in a maze.

## Breadth-First Search (BFS)
- **Principle**: Uses a queue to explore all neighbors at a current depth level before moving to the next level.
- **Process**: Starts at a node and explores all adjacent nodes, then each of their neighbors, and so on.
- **Application**: Ideal for finding the shortest path on unweighted graphs or for traversal in networks like social graphs.

## Dijkstra’s Algorithm
- **Purpose**: Finds the shortest paths from a single source to all other nodes in a weighted graph.
- **Mechanism**: Maintains a table of the shortest known distances to each node, updating paths and distances as it explores the graph.
- **Limitation**: Cannot handle negative edge weights.
- **Use**: Widely used in network routing, for example, in GPS navigation systems.

## A* Search Algorithm
- **Concept**: A more efficient form of Dijkstra's, incorporating heuristics.
- **Heuristic Function**: Estimations of distance to the goal are used to prioritize nodes likely to lead to the shortest path.
- **Use**: Effective in pathfinding and graph traversal problems, especially in computer games, AI, and robotics.

Each of these algorithms serves a specific purpose and is selected based on the requirements of the problem, such as the type of graph (weighted/unweighted, directed/undirected), the presence of negative edges, and the need for efficiency in terms of computation and memory usage.
