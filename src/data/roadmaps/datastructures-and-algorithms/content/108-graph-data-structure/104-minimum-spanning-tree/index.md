# Minimum Spanning Tree (MST)

## Definition
- **Type**: A subset of the edges of a connected, undirected graph.
- **Purpose**: Connects all vertices together with the minimum total edge weight and without forming any cycles.

## Characteristics
- **Connectivity**: Ensures that all vertices are connected.
- **No Cycles**: The tree structure means it contains no loops or circuits.
- **Minimum Total Weight**: The sum of the weights of the edges in the MST is as small as possible.

## Algorithms for Finding MST
1. **Prim's Algorithm**:
   - Builds the MST by continuously adding the shortest edge that connects a vertex in the tree to a vertex outside.
   
2. **Kruskal's Algorithm**:
   - Constructs the MST by selecting the shortest edge in the graph and ensuring that its addition doesn't form a cycle.

3. **Boruvka's Algorithm**:
   - Starts with each vertex as a separate component and repeatedly merges components with the smallest weight edge between them.

## Applications
- **Network Design**: Utilized in designing efficient networks like electrical grids, computer networks, road networks, etc.
- **Optimization**: Helps in minimizing costs while ensuring connectivity.

## Importance
- **Resource Efficiency**: Key in scenarios where the goal is to achieve some form of connectivity using minimum resources.
- **Problem Solving**: Used in various computational and real-world problems that require efficient state or structure.

Minimum Spanning Trees are fundamental in both the study of graph theory and its application in practical problems, especially those involving network optimization and cost minimization.
