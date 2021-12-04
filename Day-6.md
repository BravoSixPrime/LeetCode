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

