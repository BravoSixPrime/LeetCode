## Morris Traversal
Connect a thread from last element of the subtree to its root so you won't loose the root

## Left View
* Level traversal
* First Element of each level

## Right View
* Level traversal
* Last Element of each level

##  Bottom View
* Maintain a queue(contains root and index in map) for level traversal and map for bottom view
* Add root as index 0 in queue
* Map the front element 
* Add its children with approriate index
* Carry this process till queue is empty

## Top View
* Same as Top View just don't overwrite on already mapped elements

## Vertical Traversal
https://practice.geeksforgeeks.org/problems/print-a-binary-tree-in-vertical-order/1

* Similar to bottom view create a map to write elements for each level
* Instead of overwriting append to the element (map should be of int and vector<int> )
  
