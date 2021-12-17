## Implement StackUsing Queue
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

