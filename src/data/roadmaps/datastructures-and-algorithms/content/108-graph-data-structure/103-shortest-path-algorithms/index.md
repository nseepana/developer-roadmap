# Shortest Path Algorithms

## Dijkstra's Algorithm
- **Function**: Finds the shortest path in a graph with non-negative edge weights.
- **Mechanism**:
  - Starts from a chosen vertex and explores neighboring vertices.
  - Keeps track of the shortest known distance from the start vertex to each vertex.
  - Repeatedly updates distances to each vertex as it explores the graph.
- **Limitation**: Cannot handle graphs with negative edge weights.
- **Use Cases**: Commonly used in routing and navigation systems, network routing protocols.

## Bellman-Ford Algorithm
- **Capability**: Handles graphs with negative edge weights and can detect negative cycles.
- **Mechanism**:
  - Iteratively "relaxes" edges, checking if shorter paths can be found by going through an edge.
  - Repeats this process for each edge in the graph, for 'V-1' iterations, where 'V' is the number of vertices.
- **Key Feature**: Able to report the existence of a negative cycle in the graph.
- **Use Cases**: Useful in network routing (like RIP protocol) and in systems where negative weights are present.

## Comparison
- **Dijkstra's Algorithm**: 
  - Faster for non-negative edge weight graphs.
  - Utilizes priority queues to efficiently find the next closest vertex.
- **Bellman-Ford Algorithm**:
  - Slower due to its iterative nature, but more versatile.
  - Essential for graphs where negative edges are involved.

Both algorithms are fundamental in computer science for solving a variety of problems related to graph traversal and optimization, particularly in the contexts of network routing, pathfinding in games, and map navigation.
