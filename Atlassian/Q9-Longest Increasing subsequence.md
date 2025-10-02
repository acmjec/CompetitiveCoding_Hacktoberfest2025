Longest Increasing Subsequence (LIS)

Given an integer array nums, find the length of the longest strictly increasing subsequence.

Examples

Example 1
Input:
nums = [10,9,2,5,3,7,101,18]

Output:
4

Explanation:

One of the longest increasing subsequences is [2,3,7,101].

Example 2
Input:
nums = [0,1,0,3,2,3]

Output:
4

Explanation:

LIS is [0,1,2,3].

Example 3
Input:
nums = [7,7,7,7,7,7,7]

Output:
1

Explanation:

All elements are same, so LIS length is 1.

Constraints

1 <= nums.length <= 2500

-10^4 <= nums[i] <= 10^4

Sample Test Cases

Case 1:
Input: nums = [10,9,2,5,3,7,101,18]
Output: 4

Case 2:
Input: nums = [0,1,0,3,2,3]
Output: 4

Case 3:
Input: nums = [7,7,7,7,7,7,7]
Output: 1