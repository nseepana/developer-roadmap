# Dijkstra's Algorithm

## Description
- **Purpose**: An algorithm for finding the shortest paths between nodes in a graph.
- **Origin**: Developed by Edsger W. Dijkstra.

## Functioning
1. **Initialization**: Starts at the source node and sets tentative distance value: zero for the initial node and infinity for all other nodes.
2. **Vertex Exploration**:
   - Visits the unvisited vertex with the smallest known distance from the start node.
   - Examines its adjacent vertices, updates their tentative distances.
3. **Path Determination**: Gradually expands the area of visited vertices, updating paths and distances.

## Limitation
- **Edge Weights**: Only applicable for graphs with non-negative edge weights.

## Implementation
- **Data Structures**: Often utilizes priority queues to efficiently find the next closest vertex.
- **Efficiency**: Can be made more efficient using data structures like min-heaps.

## Time Complexity
- **Theoretical Worst-Case**: O(|V|^2), where |V| is the number of vertices.
- **Practical Performance**: Typically runs faster in practice, especially with optimized data structures.

## Applications
- **Use Cases**: Widely used in network routing, GPS navigation, and mapping services to find the shortest path between points.

Dijkstra's algorithm is celebrated for its efficiency and accuracy in pathfinding and is a cornerstone in the field of computer science, particularly in network analysis and geographic mapping.
