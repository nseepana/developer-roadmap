# Selection Sort

## How It Works
1. **Division of Array**: The array is conceptually divided into two parts - the sorted section and the unsorted section.
2. **Initial State**: At the beginning, the sorted part is empty while the unsorted part contains all the elements.
3. **Selection and Swapping**:
   - In each iteration, the algorithm selects the smallest (or largest for descending order) element from the unsorted portion.
   - This element is then swapped to the end of the sorted section.
4. **Iterative Process**: This process is repeated until the unsorted section is depleted, resulting in a fully sorted array.

## Characteristics
- **Simplicity**: Known for its straightforward approach and ease of understanding.
- **Inefficiency with Large Lists**: Not the most efficient for handling large data sets due to its time complexity.
- **Time Complexity**: Has a time complexity of O(n²), where 'n' is the number of elements in the array.

## Performance
- **Comparisons and Swaps**: Makes a large number of comparisons (nearly n²/2) and swaps (n), which contributes to its inefficiency for larger datasets.
- **Non-Adaptive**: The time complexity remains the same regardless of the initial order of the elements.

## Use Cases
- **Suitability**: Best used for small datasets or when simplicity is preferred over efficiency.
- **Limitation**: Not recommended for high-performance or large-scale sorting tasks due to its quadratic time complexity.
