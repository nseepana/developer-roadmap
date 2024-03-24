# Polynomial Time Complexity (O(n^k))

## Definition
- **Notation**: Represented as O(n^k), where 'n' is the size of the input and 'k' is a constant exponent.
- **Characteristic**: The running time increases in proportion to the input size raised to a constant power.

## Variants
- **Includes**: Various runtime complexities such as O(n) (linear), O(n²) (quadratic), O(n³) (cubic), and so on.
- **Determination of 'k'**: The constant 'k' depends on the specific algorithm and how its steps increase with input size.

## Efficiency
- **Suitability**: Considered reasonably efficient for small to medium-sized inputs.
- **Scaling Issue**: For very large inputs, the time taken can grow rapidly, making these algorithms less practical.

## Examples
- **O(n)**: Scanning an array.
- **O(n²)**: Bubble sort or insertion sort for sorting arrays.
- **O(n³)**: Certain matrix multiplication algorithms.

## Perspective
- **Practicality**: Polynomial time complexity is often seen as a threshold for algorithm efficiency – algorithms with polynomial time (or better) are usually deemed acceptable for practical use, whereas those with worse than polynomial time might not be viable for large-scale problems.
