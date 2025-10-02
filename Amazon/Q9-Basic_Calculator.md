# **Basic Calculator**

Given a string s representing a valid expression, implement a basic calculator to evaluate it, and return the result of the evaluation.

**Note**: You are not allowed to use any built-in function which evaluates strings as mathematical expressions, such as eval().

### **Example 1:**

**Input:**

s \= "1 \+ 1"

**Output:**

2

**Explanation:** The expression evaluates to the sum of 1 and 1, which is 2\.

### **Example 2:**

**Input:**

s \= "(1+(4+5+2)-3)+(6+8)"

**Output:**

23

**Explanation:** The expression is evaluated respecting the parentheses. The inner parenthesis (4+5+2) is 11\. The expression becomes (1+11-3) \+ (6+8), which simplifies to 9 \+ 14, resulting in 23\.

### **More Test Cases:**

* Input: s \= "1 \- (-2)"  
  Output: 3  
* Input: s \= " ( 3 \- (4 \- 5\) ) "  
  Output: 4  
* Input: s \= "123"  
  Output: 123

### **Constraints:**

* 1 \<= s.length \<= 3 \* 10^5  
* s consists of digits, '+', '-', '(', ')', and ' '.  
* s represents a valid expression.  
* '+' is not used as a unary operation (i.e., "+1" and "+(2 \+ 3)" is invalid).  
* '-' could be used as a unary operation (i.e., "-1" and "-(2 \+ 3)" is valid).  
* There will be no two consecutive operators in the input.  
* Every number and running calculation will fit in a signed 32-bit integer.