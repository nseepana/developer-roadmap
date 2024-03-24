# Big-θ Notation

## Definition
- **Purpose**: Big Theta (Θ) notation is a mathematical concept in computer science used to define the asymptotic tight bound of a function.
- **Functionality**: It offers both an upper and lower bound on a function's growth rate.

## Understanding Θ-notation
- **Expression**: When we say a function f(n) is Θ(g(n)), it indicates:
  - **Upper Bound**: The growth rate of f(n) does not exceed g(n) beyond a certain point.
  - **Lower Bound**: The growth rate of f(n) is at least as fast as g(n) beyond a certain point.
- **Precision**: This is more precise than Big O (upper bound only) and Big Omega (lower bound only) notations.

## Application
- **Example**: If an algorithm is described as having Θ(n²) complexity, it means:
  - **Quadratic Growth**: The running time of the algorithm increases quadratically in proportion to the input size.
  - **Tight Bound**: This notation specifies that the algorithm's time complexity will consistently grow in this manner for large input values, neither significantly faster nor slower.

## Significance
- **Accuracy**: Big Theta notation is valuable for providing an exact characterization of an algorithm's behavior, especially for large inputs, revealing its efficiency in a comprehensive manner.
