Serialize and Deserialize Binary Tree

Design an algorithm to convert a binary tree to a string (serialize) and reconstruct it back to the original tree (deserialize).

You may design your own format for serialization. The goal is to ensure the tree can be reconstructed exactly.

Examples

Example 1
Input:

    1
   / \
  2   3
     / \
    4   5


Output:

Serialized string: "1,2,null,null,3,4,null,null,5,null,null"

Deserialized tree matches the original.

Example 2
Input:
root = null

Output:

Serialized string: ""

Deserialized tree is null.

Constraints

The number of nodes in the tree is in the range [0, 10^4].

-1000 <= Node.val <= 1000

Sample Test Cases

Case 1:
Input: Tree [1,2,3,null,null,4,5]
Output: Serialized "1,2,null,null,3,4,null,null,5,null,null"

Case 2:
Input: Tree []
Output: Serialized ""