Search in Rotated Sorted Array

Suppose an array sorted in ascending order is rotated at some pivot. Given a target value, return its index if it exists in the array, otherwise return -1.

Examples

Example 1
Input:
nums = [4,5,6,7,0,1,2], target = 0

Output:
4

Explanation:

0 appears at index 4.

Example 2
Input:
nums = [4,5,6,7,0,1,2], target = 3

Output:
-1

Explanation:

3 does not appear in the array.

Constraints

1 <= nums.length <= 5000

-10^4 <= nums[i] <= 10^4

All values of nums are unique

nums is rotated at some pivot

-10^4 <= target <= 10^4

Sample Test Cases

Case 1:
Input: nums = [4,5,6,7,0,1,2], target = 0
Output: 4

Case 2:
Input: nums = [4,5,6,7,0,1,2], target = 3
Output: -1