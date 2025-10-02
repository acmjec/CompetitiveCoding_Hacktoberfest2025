Partition Equal Subset Sum
Given a non-empty array nums containing only positive integers, find if the array can be partitioned into two subsets such that the sum of elements in both subsets is equal.

Example 1:
Input:

nums = [1,5,11,5]

Output:

true

Explanation: The array can be partitioned as [1, 5, 5] and [11]. Both subsets have a sum of 11.

Example 2:
Input:

nums = [1,2,3,5]

Output:

false

Explanation: The array cannot be partitioned into two subsets with equal sums. The total sum is 11, which is odd, so it's impossible.

Constraints:
1 <= nums.length <= 200

1 <= nums[i] <= 100