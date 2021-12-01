## Set Matrix Zeroes
<b> O(1) Solution : </b>

* Iterate through all elements and set flags

* Use first cell of each row/colmumn as a flag to decide if you want to set it as 0

* Use bool variables row and col as flags to set first row or first column to zero

* for(i=1->m)
  for(j=1->n)
    if flag is set : set to zero
    
* if 'row' is set change all cells of first row to zero

* if 'col' is set change all cells of first column to zero





