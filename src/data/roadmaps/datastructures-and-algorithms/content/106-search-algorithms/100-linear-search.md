# Linear Search

## Overview
- **Type**: A basic and straightforward search algorithm.
- **Alternative Name**: Also known as sequential search.

## How It Works
1. **Sequential Checking**: Begins from the first element of the array and checks each element in turn.
2. **Process**:
   - Examines each item one by one.
   - Compares each element with the target value.
3. **Termination**:
   - **Found**: If a match is found, the search terminates.
   - **Not Found**: Continues until it reaches the end of the array without finding the match.

## Characteristics
- **Applicability**: Works on both sorted and unsorted lists.
- **Preconditions**: Does not require any prior arrangement or preprocessing of the data.

## Efficiency
- **Time Complexity**: O(n), where 'n' is the number of elements in the array.
- **Performance**: Considered less efficient compared to other search algorithms like binary search, especially for larger datasets.
- **Comparison-Based**: Checks each element against the target, making it simple but potentially time-consuming.

## Use Cases
- **Suitability**: Ideal for small datasets or situations where the list cannot be pre-sorted. Also useful for unstructured data where more complex search methods cannot be applied.
