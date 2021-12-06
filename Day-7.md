## Copy List with Random Pointer
https://leetcode.com/problems/copy-list-with-random-pointer/

* Use map<Node*,Node*> to store pointers
* Use given list as a key and copied list as value
* map[ptr] = new Node(ptr->val)
* Assign next and random
  * m[ptr]->next = m[ptr->next]
  * m[ptr]->random = m[ptr->random]
Return m[head]

