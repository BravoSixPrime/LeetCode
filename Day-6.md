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

