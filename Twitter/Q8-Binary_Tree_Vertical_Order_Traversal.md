Binary Tree Vertical Order Traversal
Given the root of a binary tree, return the vertical order traversal of its nodes' values (i.e., from top to bottom, column by column).

If two nodes are in the same row and column, the order should be from left to right.

Example 1:
Input:

root = [3,9,20,null,null,15,7]

Output:

[[9],[3,15],[20],[7]]

Explanation:
Node 9 is in column -1.
Nodes 3 and 15 are in column 0.
Node 20 is in column 1.
Node 7 is in column 2.

Example 2:
Input:

root = [3,9,8,4,0,1,7]

Output:

[[4],[9],[3,0,1],[8],[7]]

Constraints:
The number of nodes in the tree is in the range [0, 100].

-100 <= Node.val <= 100