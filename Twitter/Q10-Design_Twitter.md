Design Twitter
Design a simplified version of Twitter where users can post tweets, follow/unfollow another user, and see the 10 most recent tweets in their news feed.

Implement the Twitter class:

Twitter() Initializes your twitter object.

postTweet(int userId, int tweetId) Composes a new tweet with ID tweetId by the user userId.

getNewsFeed(int userId) Retrieves the 10 most recent tweet IDs in the user's news feed. Each item in the news feed must be posted by users who the user followed or by the user themselves. Tweets must be ordered from most recent to least recent.

follow(int followerId, int followeeId) The user with ID followerId started following the user with ID followeeId.

unfollow(int followerId, int followeeId) The user with ID followerId started unfollowing the user with ID followeeId.

Example 1:
Input:
["Twitter", "postTweet", "getNewsFeed", "follow", "postTweet", "getNewsFeed", "unfollow", "getNewsFeed"]
[[], [1, 5], [1], [1, 2], [2, 6], [1], [1, 2], [1]]

Output:
[null, null, [5], null, null, [6, 5], null, [5]]

Explanation:
Twitter twitter = new Twitter();
twitter.postTweet(1, 5); // User 1 posts a new tweet (id = 5).
twitter.getNewsFeed(1);  // User 1's news feed should return a list with 1 tweet -> [5].
twitter.follow(1, 2);    // User 1 follows user 2.
twitter.postTweet(2, 6); // User 2 posts a new tweet (id = 6).
twitter.getNewsFeed(1);  // User 1's news feed should return 2 tweets in order -> [6, 5].
twitter.unfollow(1, 2);  // User 1 unfollows user 2.
twitter.getNewsFeed(1);  // User 1's news feed should return a list with 1 tweet -> [5], since user 1 is no longer following user 2.

Constraints:
1 <= userId, followerId, followeeId <= 500

0 <= tweetId <= 10^4

All tweetIds will be unique.

At most 3 * 10^4 calls will be made to postTweet, getNewsFeed, follow, and unfollow.