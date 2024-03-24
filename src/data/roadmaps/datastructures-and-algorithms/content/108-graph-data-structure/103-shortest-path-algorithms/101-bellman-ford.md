# Bellman-Ford Algorithm

## Overview
- **Purpose**: Used to find the shortest paths from a single source vertex to all other vertices in a weighted graph.
- **Capability**: Can handle graphs with negative weight edges.

## Working Mechanism
1. **Initialization**: Starts with distances to all vertices set to infinity, except for the source vertex set to zero.
2. **Relaxation Process**:
   - Iteratively relaxes each edge, updating the shortest distance estimate for vertices.
   - Repeats for 'V-1' times, where 'V' is the number of vertices.
3. **Edge Check**: Each iteration checks if a shorter path can be found by using an edge.

## Key Points
- **Developers**: Named after Richard Bellman and Lester Ford.
- **Negative Weight Handling**: Able to deal with negative weights, unlike Dijkstra's algorithm.
- **Infinite Loop Issue**: Requires an additional check to detect negative weight cycles to avoid infinite loops.

## Negative Weight Cycles
- **Detection**: The Bellman-Ford algorithm can be modified to detect negative weight cycles in a graph.
- **Importance**: Identifying such cycles is crucial as they can make the concept of the "shortest path" undefined.

## Applications
- **Versatility**: Useful in real-world scenarios like network routing, economics, and other fields where negative weights might occur.

The Bellman-Ford algorithm is particularly valued in complex systems where the flexibility to handle negative weights is crucial. Despite being less efficient than Dijkstra's algorithm for non-negative edge graphs, its ability to detect negative cycles makes it an essential tool in graph theory and network analysis.
