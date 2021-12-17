## Implement Stack Using Queue
https://leetcode.com/problems/implement-stack-using-queues/

**Using only one queue**

All operation except pop are O(1)

Pop is O(n)

For poping perferm pop and push on queue size-1 times and finally pop the the front element

## Implement Queue using Stacks
https://leetcode.com/problems/implement-queue-using-stacks/

**Amortized O(1) time complexity**

* Take 2 stacks ip and op
* push into ip
* peek
  * If op is empty push ip into op
  * Return top of op
* pop
  * peek
  * remove top of op

## Next Greater Element I
https://leetcode.com/problems/next-greater-element-i/

**O(N)** solution

Given nums1(subset of nums2) and nums2

* First find next greater for nums2
* Use stack and array
* Push last element of nums2
* Iterate from second last element
* If top of stack is greater than current element assign to array that maintains next greater
* Push current number to stack
* Otherwise pop the top and push new element

