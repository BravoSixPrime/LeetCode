##  Rotate Image
https://leetcode.com/problems/rotate-image/

<b> Method 1 </b>
* Swap Outer elements in one cycle one by one
* Go one square inside the matrix and do the same
```cpp
  for (int i = 0; i < N / 2; i++) {
        for (int j = i; j < N - i - 1; j++) {
        
            int temp = a[i][j]; // Upper horizontal line elements
            a[i][j] = a[N - 1 - j][i]; // Left vertical line elements
            a[N - 1 - j][i] = a[N - 1 - i][N - 1 - j]; // Lower horizontal line elements
            a[N - 1 - i][N - 1 - j] = a[j][N - 1 - i]; // Right vertical line elements
            a[j][N - 1 - i] = temp;
        }
    }
```

<b> Method 2 </b>
* Take transpose of a matrix
* Mirror the matrix

## Merge Intervals
https://leetcode.com/problems/merge-intervals/
* Sort the 2D array by standard library function (it will sort by comparing the first element of array)
* Push ther first cell of array int 'ans' array
* Iterate through the intervals arr
* If second element of last element of 'ans' >= second element of interval arr then merge
* Otherwise push into ans

## Merge Sorted Array Without Extra Space
https://leetcode.com/problems/merge-sorted-array/

nums1 = [1,2,3,0,0,0] (last 3 zeros are padding)

nums2 = [2,5,6]
* Make nums1 to : [0,0,0,1,2,3]
* Take appropraite pointers p1 and p2 for 2 arrays
* Start Merging into nums1 starting with index 0
