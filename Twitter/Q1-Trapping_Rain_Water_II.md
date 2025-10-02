Trapping Rain Water II
Given an m x n integer matrix heightMap representing the height of each unit cell in a 2D elevation map, compute the volume of water it can trap after raining.

Example 1:
Input:

heightMap = [[1,4,3,1,3,2],[3,2,1,3,2,4],[2,3,3,2,3,1]]

Output:

4

Explanation: After the rain, water is trapped between the walls. The total volume of trapped water is 4.

Example 2:
Input:

heightMap = [[3,3,3,3,3],[3,0,0,0,3],[3,0,5,0,3],[3,0,0,0,3],[3,3,3,3,3]]

Output:

10

Explanation: The water is trapped in the 0-height cells, held by the walls of height 3 and the inner peak of height 5.

Constraints:
m == heightMap.length

n == heightMap[i].length

1 <= m, n <= 200

0 <= heightMap[i][j] <= 2 * 10^4