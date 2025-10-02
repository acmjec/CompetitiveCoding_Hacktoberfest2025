# **Next Greater Element III**

Given a positive integer n, find the smallest integer which has exactly the same digits existing in the integer n and is greater in value than n. If no such positive integer exists, return \-1.

Note that the returned integer should fit in a 32-bit integer; if there is a valid answer but it does not fit in a 32-bit integer, return \-1.

### **Example 1:**

**Input:**

n \= 12

**Output:**

21

**Explanation:** By rearranging the digits of 12, we can form 21\. This is the smallest number greater than 12 using the same digits.

### **Example 2:**

**Input:**

n \= 21

**Output:**

\-1

**Explanation:** The only other permutation of the digits is 12, which is smaller than 21\. There is no greater integer with the same digits.

### **More Test Cases:**

* Input: n \= 1243  
  Output: 1324  
* Input: n \= 4321  
  Output: \-1  
* Input: n \= 1999999999  
  Output: \-1

### **Constraints:**

* 1 \<= n \<= 2^31 \- 1