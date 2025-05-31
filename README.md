# Day32-50-days-coding-challenge

## Problem 1: Binary Tree Level Order Traversal

- Perform a breadth-first search (BFS) using a queue.
- Collect nodes level by level, adding them to the output list.
- Constraints:
  - Number of nodes: 0 to 2000
  - Node values: [-1000, 1000]
- Time Complexity: O(N), where N is the number of nodes.
- Space Complexity: O(N), for storing the queue and output.

**Example:**  
Input: [3,9,20,null,null,15,7]  
Output: [[3],[9,20],[15,7]]

---

## Problem 2: Rotate Image (90 Degrees Clockwise)

- Rotate an n x n matrix in-place by 90 degrees clockwise.
- Do not use extra memory for a new matrix.
- Approach:
  - Transpose the matrix (swap elements across the diagonal).
  - Reverse each row to achieve a 90-degree rotation.
- Constraints:
  - 1 <= n <= 20
  - Matrix values: [-1000, 1000]
- Time Complexity: O(n^2)
- Space Complexity: O(1)

**Example:**  
Input: [[1,2,3],[4,5,6],[7,8,9]]  
Output: [[7,4,1],[8,5,2],[9,6,3]]

---

Stay tuned for Day 33! 🚀  
This challenge is part of the #DrGViswanathanChallenge.
