## Longest Consecutive Sequence
https://leetcode.com/problems/longest-consecutive-sequence/

Solution : 
https://leetcode.com/problems/longest-consecutive-sequence/discuss/41088/Possibly-shortest-cpp-solution-only-6-lines.

## Longest Substring Without Repeating Characters
https://leetcode.com/problems/longest-substring-without-repeating-characters/

* Consider a set that takes in alphabets
* 2 markers l & r
* If incoming character s[r] is not in set then insert and increment sliding window and r++
* else remove s[l] from set and l++
* Return max sliding window


