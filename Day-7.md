## Copy List with Random Pointer
https://leetcode.com/problems/copy-list-with-random-pointer/

* Use map<Node*,Node*> to store pointers
* Use given list as a key and copied list as value
* map[ptr] = new Node(ptr->val)
* Assign next and random
  * m[ptr]->next = m[ptr->next]
  * m[ptr]->random = m[ptr->random]
Return m[head]

## Trapping Rainwater
TC:O(n) SC:O(n)
* Maintain 2 arrays ; lmax and rmax
* Water on level i = min(lmax[i],rmax[i]) - height[i]
* Add all the levels to get total water

TC:O(n) SC:O(1)
```cpp
int trap(vector<int>& height) {
    int l = 0, r = height.size()-1, level = 0, water = 0;
    while (l < r) {
        int lower = height[height[l] < height[r] ? l++ : r--];
        level = max(level, lower);
        water += level - lower;
    }
    return water;
}
```
