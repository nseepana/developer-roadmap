# Heap Sort

## Concept
- **Type**: A comparison-based, efficient sorting algorithm.
- **Data Structure**: Uses a binary heap for its operations.

## Working Principle
1. **Binary Heap Construction**: First, it builds a Max-Heap, a special tree-based structure where each parent node is greater than its child nodes.
2. **Sorting Process**:
   - **Splitting**: Divides the input into two regions - sorted and unsorted.
   - **Extracting and Swapping**: Iteratively removes the largest element from the heap (root of the Max-Heap) and swaps it with the last element in the unsorted region.
   - **Heapify**: After each swap, the algorithm heapifies the remaining unsorted region, maintaining the Max-Heap property.
   - **Shrinking Unsorted Region**: Continues until the unsorted region is empty, effectively growing the sorted region.

## Characteristics
- **In-Place**: Does not require extra space for another array, but rearranges elements within the given array.
- **Not Stable**: May change the relative order of equal elements.
- **Efficiency**: Consistently maintains a time complexity of O(n log n) in all cases - best, average, and worst.

## Advantages
- **Worst-Case Efficiency**: Unlike other sorting algorithms like Quick Sort, Heap Sort guarantees a worst-case time complexity of O(n log n).
- **Space Efficiency**: As an in-place algorithm, it is space-efficient, requiring only a constant amount of additional memory space.

## Application
- **Use Case**: Suitable for cases where consistent runtime performance is essential, and memory space is a concern. However, due to its non-stable nature, it may not be ideal for situations where the relative ordering of similar elements is crucial.
