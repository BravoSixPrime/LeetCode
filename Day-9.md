## Subsets II
https://leetcode.com/problems/subsets-ii/

* 2D ans array
* sort nums(given aray)
* temp array
* Util function(nums,ans,temp,j)
  * push temp into ans
  * for(i=j to nums.size() )
    
     <b>if i==j || nums[i-1] !=nums[i]</b>
    
     push nums[i] to temp
     call the function for current state
     pop from temp
 
## Combination Sum
https://leetcode.com/problems/combination-sum/

* Keep taking the same number till you get to answer or number greater than answer
* If sum = target then push the temp array
* Remove the last number and call function for given temp array
* If you encounter incoming candidate lesser than the last element of the temp array skip it to avoid repetition

