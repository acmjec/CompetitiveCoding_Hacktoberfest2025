Valid Parentheses

Given a string s containing just the characters '(', ')', '{', '}', '[', and ']', determine if the input string is valid.

An input string is valid if:

Open brackets must be closed by the same type of brackets.

Open brackets must be closed in the correct order.

Every close bracket has a corresponding open bracket of the same type.

Examples

Example 1
Input:
s = "()"

Output:
true

Explanation:
The string has one opening and one closing parenthesis in correct order.

Example 2
Input:
s = "()[]{}"

Output:
true

Explanation:
The string has all types of brackets and they all close properly in correct order.

Example 3
Input:
s = "(]"

Output:
false

Explanation:
The brackets do not match correctly.

Constraints

1 <= s.length <= 10^4

s consists of parentheses only '()[]{}'.

Sample Test Cases

Case 1:
Input: s = "()"
Output: true

Case 2:
Input: s = "([)]"
Output: false

Case 3:
Input: s = "{[]}"
Output: true