## Longest Palindromic String
https://leetcode.com/problems/longest-palindromic-substring/

Use 2d DP
* For sliding windows of all sizes keep track whether that window is palindromic
* For checking if string is palidromic use dp array
* Return largest palindromic window string


## Roman to Integer
https://leetcode.com/problems/roman-to-integer/

* initialize ans to int(last element)
* start from the second last element of string
* if incoming element >=  its next element then increase
* Otherwise deacrease
* return ans



