# How to Calculate Complexity?

## Understanding Big O Notation
- **Purpose**: Big O notation is used to express the number of operations or steps an algorithm takes relative to the size of its input.
- **Focus**: The method is designed to determine the worst-case, average-case, and best-case complexities.

## Calculating Worst-Case Complexity
- **Primary Concern**: Focus is typically on the worst-case scenario, which shows the maximum steps an algorithm takes.
- **Method**: Identify the highest order of the input size (n) in the algorithm's steps.

## Examples
- **O(1)**: Represents constant complexity; the number of steps doesn’t change regardless of input size.
- **O(n)**: Linear complexity; steps increase linearly with the size of the input. For example, a loop that runs 'n' times.
- **O(n^2)**: Quadratic complexity; steps increase quadratically with the input size. This often occurs with nested loops.
- **Determining Complexity**: If an algorithm includes a loop that runs 5 times for each 'n' items and performs 3 additional unrelated steps, its complexity is O(n). Here, the linearly growing steps (the loop) are the dominant factor as 'n' increases, overshadowing the constant steps.

## Key Principle
- **Understanding Growth**: Complexity is calculated based on how steps increase with the size of the input. The focus is on the term that grows the fastest as the input size increases.
