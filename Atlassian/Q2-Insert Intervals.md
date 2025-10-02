Insert Interval

Given a set of non-overlapping intervals intervals sorted by their start time, insert a new interval newInterval into intervals such that the intervals remain non-overlapping and sorted. Merge intervals if necessary.

Examples

Example 1
Input:

intervals = [[1,3],[6,9]], newInterval = [2,5]


Output:

[[1,5],[6,9]]


Explanation:

The new interval [2,5] overlaps with [1,3], so merge them into [1,5].

Example 2
Input:

intervals = [[1,2],[3,5],[6,7],[8,10],[12,16]], newInterval = [4,8]


Output:

[[1,2],[3,10],[12,16]]


Explanation:

New interval [4,8] overlaps with [3,5],[6,7],[8,10], so they are merged into [3,10].

Constraints

0 <= intervals.length <= 10^4

intervals[i].length == 2

0 <= start_i <= end_i <= 10^5

newInterval.length == 2

0 <= newInterval[0] <= newInterval[1] <= 10^5

Sample Test Cases

Case 1:
Input: intervals = [[1,3],[6,9]], newInterval = [2,5]
Output: [[1,5],[6,9]]

Case 2:
Input: intervals = [[1,2],[3,5],[6,7],[8,10],[12,16]], newInterval = [4,8]
Output: [[1,2],[3,10],[12,16]]