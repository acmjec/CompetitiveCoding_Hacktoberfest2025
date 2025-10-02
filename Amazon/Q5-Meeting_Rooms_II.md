# **Meeting Rooms II**

You are given a list of time intervals representing the start and end times of various events. Each interval is a string formatted as "start, end". The intervals are half-open, meaning an interval \[start, end) includes the start time but excludes the end time.

Determine the minimum number of conference rooms required to accommodate all events.

### **Example 1:**

**Input:**

\["1, 10", "2, 6", "5, 15"\]

**Output:**

3

**Explanation:** At time 5, three events are happening concurrently: \[1, 10), \[2, 6), and \[5, 15). Therefore, a minimum of 3 rooms is required.

### **Example 2:**

**Input:**

\["1, 5", "2, 6", "8, 10"\]

**Output:**

2

**Explanation:** The first two events, \[1, 5\) and \[2, 6), overlap and require two separate rooms. The third event, \[8, 10), can reuse one of the rooms after the first two have finished.

### **More Test Cases:**

* Input: \["1, 5", "6, 8", "9, 10"\]  
  Output: 1  
* Input: \["0, 10", "0, 5", "0, 15"\]  
  Output: 3  
* Input: \["1, 4", "5, 8", "2, 6"\]  
  Output: 2

### **Constraints:**

* 1 ≤ number of intervals ≤ 12,000  
* 0 ≤ start \< end ≤ 100,000  
* Intervals may be given in any order.