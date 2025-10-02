Top K Frequent Elements

Given an integer array nums and an integer k, return the k most frequent elements. You may return the answer in any order.

Examples

Example 1
Input:
nums = [1,1,1,2,2,3], k = 2

Output:
[1,2]

Explanation:

1 appears 3 times, 2 appears 2 times.

Example 2
Input:
nums = [1], k = 1

Output:
[1]

Explanation:

Only one element in the array.

Constraints

1 <= nums.length <= 10^5

k is in the range [1, number of unique elements in nums]

Sample Test Cases

Case 1:
Input: nums = [1,1,1,2,2,3], k = 2
Output: [1,2]

Case 2:
Input: nums = [1], k = 1
Output: [1]