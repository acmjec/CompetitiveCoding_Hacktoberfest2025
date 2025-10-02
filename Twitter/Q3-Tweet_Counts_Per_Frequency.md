Tweet Counts Per Frequency
A social media company is trying to monitor activity on their site by analyzing the number of tweets over certain time intervals. Implement the TweetCounts class.

TweetCounts() Initializes the object.
recordTweet(string tweetName, int time) Stores the tweetName at the given time (in seconds).
getTweetCountsPerFrequency(string freq, string tweetName, int startTime, int endTime) Returns a list of integers representing the number of tweets per interval.

Example 1:
Input:
["TweetCounts","recordTweet","recordTweet","recordTweet","getTweetCountsPerFrequency","getTweetCountsPerFrequency","recordTweet","getTweetCountsPerFrequency"]
[[],["tweet3",0],["tweet3",60],["tweet3",10],["minute","tweet3",0,59],["minute","tweet3",0,60],["tweet3",120],["hour","tweet3",0,210]]

Output:
[null,null,null,null,[2],[2],null,[4]]

Explanation:
TweetCounts tweetCounts = new TweetCounts();
tweetCounts.recordTweet("tweet3", 0);
tweetCounts.recordTweet("tweet3", 60);
tweetCounts.recordTweet("tweet3", 10);
tweetCounts.getTweetCountsPerFrequency("minute", "tweet3", 0, 59); // return [2] The tweets happen at time 0 and 10, both are in the first minute.
tweetCounts.getTweetCountsPerFrequency("minute", "tweet3", 0, 60); // return [2] The tweets happen at time 0 and 10 in the first minute, and at time 60 in the second minute.
tweetCounts.recordTweet("tweet3", 120);
tweetCounts.getTweetCountsPerFrequency("hour", "tweet3", 0, 210); // return [4] All tweets are in the first hour.

Constraints:
0 <= time, startTime, endTime <= 10^9

tweetName consists of lowercase English letters and digits.

freq is one of "minute", "hour", or "day".

At most 10^4 calls will be made to recordTweet and getTweetCountsPerFrequency.