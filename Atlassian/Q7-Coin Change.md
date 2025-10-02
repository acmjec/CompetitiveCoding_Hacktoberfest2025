Coin Change (Minimum Coins)

Given a list of coin denominations coins and an integer amount, compute the minimum number of coins required to make up the amount. If it is not possible, return -1.

Examples

Example 1
Input:
coins = [1,2,5], amount = 11

Output:
3

Explanation:

11 can be made with 5 + 5 + 1 = 3 coins.

Example 2
Input:
coins = [2], amount = 3

Output:
-1

Explanation:

Cannot make 3 using only 2-value coins.

Example 3
Input:
coins = [1], amount = 0

Output:
0

Explanation:

Zero amount requires zero coins.

Constraints

1 <= coins.length <= 12

1 <= coins[i] <= 2^31 - 1

0 <= amount <= 10^4

Sample Test Cases

Case 1:
Input: coins = [1,2,5], amount = 11
Output: 3

Case 2:
Input: coins = [2], amount = 3
Output: -1

Case 3:
Input: coins = [1], amount = 0
Output: 0