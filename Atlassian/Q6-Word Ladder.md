Word Ladder (Length of Shortest Transformation)

Given two words beginWord and endWord, and a dictionary wordList, find the length of the shortest transformation sequence from beginWord to endWord. You can change only one letter at a time, and each transformed word must exist in wordList.

Examples

Example 1
Input:
beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log","cog"]

Output:
5

Explanation:

One shortest transformation is "hit" -> "hot" -> "dot" -> "dog" -> "cog", length 5.

Example 2
Input:
beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log"]

Output:
0

Explanation:

endWord "cog" is not in wordList, so no transformation is possible.

Constraints

1 <= beginWord.length <= 10

endWord.length == beginWord.length

1 <= wordList.length <= 5000

wordList[i].length == beginWord.length

beginWord, endWord, and wordList[i] consist of lowercase English letters.

Sample Test Cases

Case 1:
Input: beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log","cog"]
Output: 5

Case 2:
Input: beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log"]
Output: 0