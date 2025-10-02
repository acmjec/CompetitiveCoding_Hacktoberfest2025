Autocomplete System
Design a search autocomplete system for a search engine. Users may input a sentence (at least one word and end with a special character '#').

For each character they type except '#', you need to return the top 3 historical hot sentences that have the same prefix as the part of the sentence already typed.

Example 1:
Input:
["AutocompleteSystem", "input", "input", "input", "input"]
[[["i love you", 5], ["island", 3], ["ironman", 2], ["i love leetcode", 2]], "i", " ", "a", "#"]

Output:
[null, ["i love you", "island", "i love leetcode"], ["i love you", "i love leetcode"], [], []]

Explanation:
AutocompleteSystem as = new AutocompleteSystem(...)
as.input('i'); // return ["i love you", "island", "i love leetcode"]
as.input(' '); // return ["i love you", "i love leetcode"]
as.input('a'); // return []
as.input('#'); // return [], the user finished the input.

Constraints:
sentences will have length between 1 and 100.

times will have length between 1 and 100.

sentences[i] and times[i] will have the same length.

The length of sentences[i] will be between 1 and 100.

The number of calls to input will be between 1 and 500.