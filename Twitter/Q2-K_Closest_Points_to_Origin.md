K Closest Points to Origin
Given an array of points where points[i] = [xi, yi] represents a point on the X-Y plane and an integer k, return the k closest points to the origin (0, 0).

The distance between two points on the X-Y plane is the Euclidean distance (i.e., √(x1 - x2)^2 + (y1 - y2)^2).

You may return the answer in any order. The answer is guaranteed to be unique (except for the order that it is in).

Example 1:
Input:

points = [[1,3],[-2,2]], k = 1

Output:

[[-2,2]]

Explanation:
The distance between (1, 3) and the origin is sqrt(10).
The distance between (-2, 2) and the origin is sqrt(8).
Since sqrt(8) < sqrt(10), (-2, 2) is closer to the origin.
We only need the closest k = 1 points, so the answer is [[-2,2]].

Example 2:
Input:

points = [[3,3],[5,-1],[-2,4]], k = 2

Output:

[[3,3],[-2,4]]

Explanation: The distance for [3,3] is sqrt(18), for [5,-1] is sqrt(26), and for [-2,4] is sqrt(20). The two closest points are [3,3] and [-2,4].

Constraints:
1 <= k <= points.length <= 10^4

-10^4 < xi, yi < 10^4