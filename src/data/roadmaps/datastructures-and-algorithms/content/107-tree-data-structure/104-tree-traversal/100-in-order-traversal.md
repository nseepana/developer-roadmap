# In-Order Traversal

## Description
- **Type**: A specific method of traversing binary trees.
- **Traversal Order**: Left Node/Subtree, Root Node, then Right Node/Subtree.

## Traversal Process
1. **Left Subtree**: Begins with the leftmost node, traversing the entire left subtree.
2. **Root Node**: After completing the left subtree, visits the root node.
3. **Right Subtree**: Finally, proceeds to explore the right subtree.

## Characteristics
- **Recursive Nature**: Typically implemented recursively, requiring each subtree to be traversed in the same manner.
- **Ascending Order in BST**: In a binary search tree (BST), in-order traversal results in nodes being visited in ascending order.

## Applications
- **Sorted Output**: Particularly useful in BSTs where a sorted order of node values is required.
- **Binary Trees Manipulation**: Essential for operations where a node's processing depends on its subtrees.

## Implementation
- **Standard Approach**: Involves visiting nodes starting from the leftmost and proceeding according to the L-N-R sequence.
- **Iterative Methods**: While less common, it can also be achieved iteratively using a stack.

## Importance
- In-order traversal is crucial in applications that require sorted traversal of binary trees, like BSTs, and in scenarios where a specific sequence of node processing is necessary.
