## Intersection of Two Linked Lists
https://leetcode.com/problems/intersection-of-two-linked-lists/

We traverse till we collide
* 2 pointer pA and pB
```cpp
while(pA != pB){
  pA = pA ? pA->next : headB;
  pB = pB ? pB->next : headA;
}
return pA;
```

## Linked List Cycle
https://leetcode.com/problems/linked-list-cycle/

Traversing till collision
* 2 pointer fast and slow
* slow = slow->next
* fast = fast->next->next
* If they collide return true

## Palindrome Linked List
https://leetcode.com/problems/palindrome-linked-list/

TC : O(n), SC:O(1)

* Reverse the second half of the linked list
* 2 markers(pointers) starting from first half and reversed second half
* If value of 2 nodes is unequa at any point return false
* return true;

## Linked List Cycle II
https://leetcode.com/problems/linked-list-cycle-ii/

TC : O(n), SC:O(1)

* fast and slow pointers
* when the collide
  * start entry pointer from head and start slow pointer
  * when slow and entry collide return entry
* return NULL

## Rotate List
https://leetcode.com/problems/rotate-list/description/

* Reverse entire List
* Reverse first k%length elements 
* Reverse remaining elements



