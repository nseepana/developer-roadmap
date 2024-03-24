# AVL Trees

## Definition
- **Type**: A self-balancing binary search tree.
- **Inventors**: Named after G.M. Adelson-Velsky and E.M. Landis (1962).

## Balancing Mechanism
- **Balance Factor**: Each node stores additional information known as its Balance Factor, which can be -1, 0, or +1.
- **Height Balance Rule**: The heights of the two child subtrees of any node differ by at most one.
- **Rebalancing**: If the balance is disrupted (difference > 1), rotations are performed to restore balance.

## Types of Rotations
1. **Left-Left (LL) Rotation**: Applied when a new node is added to the left subtree of the left child.
2. **Right-Right (RR) Rotation**: Applied when a new node is added to the right subtree of the right child.
3. **Left-Right (LR) Rotation**: Applied when a new node is added to the right subtree of the left child.
4. **Right-Left (RL) Rotation**: Applied when a new node is added to the left subtree of the right child.

## Characteristics
- **Automatic Balancing**: Adjusts itself with every insertion and deletion to maintain balance.
- **Performance**: Provides better performance for lookup-intensive applications due to its balanced nature.

## Advantages
- **Efficient Operations**: Lookups, insertions, and deletions take O(log n) time in the worst case.
- **Data Structure Optimization**: Ensures that the tree does not become significantly unbalanced, which can degrade performance.

## Use Cases
- **Ideal for**: Systems requiring frequent insertions/deletions and where balanced height is crucial to maintain efficiency, such as in database applications and memory management systems.

## Significance
- **Stability and Efficiency**: AVL trees are a foundational data structure in computer science, offering a robust and efficient way to maintain a balanced binary search tree.
