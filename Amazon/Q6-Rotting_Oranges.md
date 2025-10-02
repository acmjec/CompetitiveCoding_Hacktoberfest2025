# **Rotting Oranges**

You are given an m x n grid where each cell can have one of three values:

* 0 representing an empty cell,  
* 1 representing a fresh orange, or  
* 2 representing a rotten orange.

Every minute, any fresh orange that is 4-directionally adjacent to a rotten orange becomes rotten.

Return the minimum number of minutes that must elapse until no cell has a fresh orange. If this is impossible, return \-1.

### **Example 1:**

**Input:**

grid \= \[\[2,1,1\],\[1,1,0\],\[0,1,1\]\]

**Output:**

4

**Explanation:** The initial rotten orange at (0,0) starts a chain reaction. The process takes 4 minutes for the fresh orange at (2,2) to finally rot.

### **Example 2:**

**Input:**

grid \= \[\[2,1,1\],\[0,1,1\],\[1,0,1\]\]

**Output:**

\-1

**Explanation:** The orange in the bottom left corner (row 2, column 0\) is never rotten, because rotting only happens 4-directionally and it's isolated by empty cells.

### **More Test Cases:**

* Input: grid \= \[\[0,2\]\]  
  Output: 0  
* Input: grid \= \[\[1,1\],\[1,1\]\]  
  Output: \-1  
* Input: grid \= \[\[2,0,1\],\[1,1,2\],\[0,1,1\]\]  
  Output: 2

### **Constraints:**

* m \== grid.length  
* n \== grid\[i\].length  
* 1 \<= m, n \<= 10  
* grid\[i\]\[j\] is 0, 1, or 2\.