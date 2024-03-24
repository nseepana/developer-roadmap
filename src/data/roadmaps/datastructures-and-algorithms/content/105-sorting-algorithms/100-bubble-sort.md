# Bubble Sort

## Description
- **Type**: A straightforward sorting algorithm.
- **Mechanism**: Involves repeated swapping of adjacent elements if they are in the incorrect order.

## Working Principle
1. **Iteration**: The algorithm iterates over the entire list.
2. **Swapping**:
   - Compares each pair of adjacent items.
   - If they are in the wrong order (based on the sorting criteria), they are swapped.
3. **"Bubbling" Effect**: The largest (or smallest, depending on sorting order) element bubbles up to its correct position with each pass through the list.
4. **Completion Criteria**: Continues this process until no further swaps are needed, indicating the list is sorted.

## Time Complexity
- **Worst-Case and Average**: O(n²), where 'n' is the number of items.
- **Inefficient for Large Datasets**: Due to its quadratic time complexity, Bubble Sort is not practical for large lists.

## Characteristics
- **Simplicity**: Easy to understand and implement.
- **Stability**: Maintains the relative order of equal elements.

## Advantages
- **Applicability**: Works well for small lists or when simplicity is a priority.
- **Visual Teaching Tool**: Often used for educational purposes to demonstrate basic sorting principles.

## Limitations
- **Inefficiency**: Due to its high time complexity, it is not suitable for scenarios where performance is critical, particularly with large data sets.
