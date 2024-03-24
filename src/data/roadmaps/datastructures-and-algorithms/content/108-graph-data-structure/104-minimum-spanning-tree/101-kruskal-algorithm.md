# Kruskal's Algorithm

## Overview
- **Type**: An algorithm for finding the Minimum Spanning Tree (MST) of a graph.
- **Developer**: Joseph Kruskal (1956).

## Working Mechanism
1. **Edge Sorting**: Sorts all edges in the graph in ascending order based on their weights.
2. **Edge Selection**:
   - Iterates through the sorted edges.
   - Adds each edge to the spanning tree, provided it doesn't create a cycle.
3. **Completion**: Continues until all vertices in the graph are connected in the spanning tree.

## Classification
- **Greedy Algorithm**: Follows a greedy approach, making the locally optimal choice at each step with the aim of finding a global optimum.

## Time Complexity
- **Performance**: O(E log E) or O(E log V), where E is the number of edges and V is the number of vertices in the graph.
- **Efficiency**: The time complexity mainly stems from the edge sorting process.

## Applications
- **Network Design**: Useful in various network designs and optimization problems.
- **Optimal Connectivity**: Employed in scenarios requiring the connection of different points at the minimum possible cost.

## Importance
- Kruskal's algorithm is valued for its simplicity and effectiveness in finding the minimum spanning tree, especially in cases where the graph is sparse and the number of edges is relatively low compared to the number of vertices.
