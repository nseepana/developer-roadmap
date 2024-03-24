# Binary Search

## Overview
- **Type**: An efficient search algorithm using the divide and conquer approach.
- **Prerequisite**: Operates on a sorted array.

## How It Works
1. **Initial Search Space**: Starts with the entire array.
2. **Mid-Point Comparison**:
   - Compares the target with the middle element of the array.
3. **Divide and Conquer**:
   - If the target equals the middle element, the search concludes.
   - If not, it eliminates the half of the array where the target cannot be.
   - The search then continues on the remaining half.
4. **Iterative or Recursive**: This process repeats, each time halving the search space.
5. **Termination**:
   - **Found**: Ends when the target is found.
   - **Not Found**: Concludes if the remaining half is empty, indicating the target isn't in the array.

## Time Complexity
- **Efficiency**: O(log n), with 'n' being the number of elements in the array.
- **Performance**: Significantly more efficient than linear search, especially for large datasets.

## Characteristics
- **Requirement**: The array must be sorted for binary search to work correctly.
- **Search Reduction**: Cuts down the search space by half in each step, leading to a logarithmic time complexity.

## Use Cases
- **Suitability**: Ideal for large datasets where the elements are pre-sorted. Used frequently in scenarios requiring quick searches, like database lookups and large-scale indexing systems.
