# **Concatenated Words**

Given an array of strings words (without duplicates), return all the **concatenated words** in the given list of words.

A **concatenated word** is defined as a string that is comprised entirely of at least two shorter words (not necessarily distinct) in the given array.

### **Example 1:**

**Input:**

words \= \["cat","cats","catsdogcats","dog","dogcatsdog","hippopotamuses","rat","ratcatdogcat"\]

**Output:**

\["catsdogcats","dogcatsdog","ratcatdogcat"\]

**Explanation:** "catsdogcats" can be concatenated by "cats", "dog", and "cats"; "dogcatsdog" can be concatenated by "dog", "cats", and "dog"; "ratcatdogcat" can be concatenated by "rat", "cat", "dog", and "cat".

### **Example 2:**

**Input:**

words \= \["cat","dog","catdog"\]

**Output:**

\["catdog"\]

**Explanation:** "catdog" is a concatenated word because it can be formed by "cat" and "dog", which are both in the input list.

### **More Test Cases:**

* Input: words \= \["a", "b", "ab", "abc"\]  
  Output: \["ab"\]  
* Input: words \= \["a", "aa", "aaa"\]  
  Output: \["aa", "aaa"\]  
* Input: words \= \["test", "testing", "tester"\]  
  Output: \[\]

### **Constraints:**

* 1 \<= words.length \<= 10^4  
* 1 \<= words\[i\].length \<= 30  
* words\[i\] consists of only lowercase English letters.  
* All the strings of words are **unique**.  
* 1 \<= sum(words\[i\].length) \<= 10^5