# Insertion Sort

## Overview
- **Type**: A simple, intuitive sorting algorithm.
- **Mechanism**: Builds the final sorted array or list incrementally, one item at a time.

## How It Works
1. **Iteration**: The algorithm iterates through the input elements.
2. **Sorting Process**:
   - In each iteration, it selects one element from the unsorted part.
   - Finds the correct position for this element within the already sorted section.
   - Inserts the element in its proper place.
3. **Completion**: This process continues until there are no more unsorted elements.

## Efficiency
- **Comparison to Advanced Algorithms**: Less efficient than more complex algorithms (like quicksort, heapsort, or merge sort) for large lists.
- **Optimal Conditions**: Performs best with small or partially sorted lists.

## Advantages
- **Simplicity**: Easy to understand and implement.
- **Adaptive**: Efficient for data sets that are already substantially sorted.
- **Online Sorting**: Capable of sorting a list as it receives it, making it useful in scenarios where data is continuously added.

## Characteristics
- **Stability**: Maintains the relative order of equal elements, making it a stable sort.
- **In-Place**: Requires only a constant amount of additional memory space.

## Use Cases
- **Suitability**: Ideal for small data sets, or when simplicity is a priority over efficiency. Also useful when data is received in a stream and must be sorted on the fly.
