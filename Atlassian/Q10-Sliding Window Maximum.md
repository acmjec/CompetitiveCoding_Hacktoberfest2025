Sliding Window Maximum

Given an integer array nums and an integer k, return an array of the maximum values in each sliding window of size k.

Examples

Example 1
Input:
nums = [1,3,-1,-3,5,3,6,7], k = 3

Output:
[3,3,5,5,6,7]

Explanation:

Window [1,3,-1] → max 3

Window [3,-1,-3] → max 3

Window [ -1,-3,5] → max 5 … and so on.

Example 2
Input:
nums = [1], k = 1

Output:
[1]

Explanation:

Only one window with one element.

Constraints

1 <= nums.length <= 10^5

-10^4 <= nums[i] <= 10^4

1 <= k <= nums.length

Sample Test Cases

Case 1:
Input: nums = [1,3,-1,-3,5,3,6,7], k = 3
Output: [3,3,5,5,6,7]

Case 2:
Input: nums = [1], k = 1
Output: [1]

Case 3:
Input: nums = [9,11], k = 2
Output: [11]