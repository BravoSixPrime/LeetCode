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

## Min Stack
https://leetcode.com/problems/min-stack/

* Use 2 stacks
* One for elements one for minimum element
* For minimum element stack : top element = min(top,new element)

## Rotting Oranges
https://leetcode.com/problems/rotting-oranges/

**BFS**

* Use time matrix to keep track of time for rotting
* Initialize rotten oranges time to 0 mins and other cells to INT_MAX
* Call bfs in 4 direction for each rotten cell
* Update the time to minimum

Finally Return Max time form time matrix
