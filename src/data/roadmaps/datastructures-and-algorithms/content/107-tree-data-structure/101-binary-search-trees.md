# Binary Search Trees (BST)

## Overview
- **Type**: A node-based binary tree data structure.
- **Unique Feature**: Each node carries a unique key or value.

## Key Properties
- **Ordering**:
  - **Right Subtree**: All nodes have values greater than their parent node.
  - **Left Subtree**: All nodes have values less than their parent node.
  - This property applies to every node, not just the root.

## Operations
- **Searching**: BST property allows binary search to be performed.
- **Insertion**: New nodes are added while maintaining the BST property.
- **Deletion**: Nodes can be removed with adjustments to preserve the tree structure.

## Performance
- **Time Complexity**:
  - Typically, O(log n) for searching, insertion, and removal.
  - This efficiency assumes the tree is balanced.
- **Worst Case**: In unbalanced trees (like a linear chain), operations can degrade to O(n).

## Advantages
- **Efficiency**: Provides fast search, insertion, and deletion operations.
- **Data Management**: Well-suited for managing dynamic data, allowing ordered storage and quick retrieval.

## Suitability
- **Use Case**: Ideal for collections where frequent insertion, deletion, and look-up of elements are required.
- **Caveat**: Efficiency relies on the tree being well-balanced.

## Importance
- **Data Structure Optimization**: BSTs are fundamental in computer science, used in various applications like database systems, file systems, and more, due to their efficiency in handling dynamic, sortable data.
