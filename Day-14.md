## Next Smaller Element
https://www.interviewbit.com/problems/nearest-smaller-element/

**O(N) solution**

* Use stack and array G(answer)
* Push first element of A
* Iterate from second element
* If top of stack is <= current element assign to array G
* Push current number to stack
* Otherwise pop the top and push new element

## Sliding Window Maximum
https://leetcode.com/problems/sliding-window-maximum/

* Use double queue
* First insert k elements 
* Iterate for remaining
* Insert front element into answer vector
* Remove elements from front and back logically

