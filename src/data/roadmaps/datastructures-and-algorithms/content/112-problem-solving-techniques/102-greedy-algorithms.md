# Greedy Algorithms

## Concept
- **Approach**: An algorithmic paradigm that makes the best or most optimal choice at each step.
- **Objective**: To find a global optimum (maximum or minimum) for a given problem.

## Characteristics
- **Local Optimum**: At each step, it chooses the option that seems the best at that moment.
- **No Reconsideration**: Once a choice is made, it is never reconsidered.
- **Shortsightedness**: Does not consider the bigger picture; focuses only on immediate benefits.

## Applications
- **Kruskal’s Algorithm**: For finding the minimum spanning tree in a graph.
- **Dijkstra’s Algorithm**: To find the shortest path from a single source in a graph.
- **Knapsack Problem**: Greedy approach works for the fractional knapsack problem but not for the 0/1 knapsack problem.

## Advantages
- **Efficiency**: Often provides faster solutions compared to other methods like dynamic programming.
- **Simplicity**: Easier to conceptualize and implement.

## Limitations
- **Suboptimal Solutions**: May not always provide the most optimal solution for all types of problems.
- **Specificity**: Only effective for problems where local optimization leads to a global solution.

Greedy algorithms are powerful in situations where making locally optimal choices also leads to a globally optimal solution. They are particularly useful for certain types of optimization problems where efficiency and simplicity are key considerations.
