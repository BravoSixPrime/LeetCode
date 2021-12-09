## N meetings in one room
https://practice.geeksforgeeks.org/problems/n-meetings-in-one-room-1587115620/1

* Take a 2D array of n X 2 with start and end time
* Sort according to end time
* Iterate from second element of array
* Take 2 variables time_limit(initialize to end time of first meeting) from last meeting and counter(inititalize to 1)
* Return counter

## Minimum Platforms
https://practice.geeksforgeeks.org/problems/minimum-platforms-1587115620/1#

* Combine arrival and departure array into a set of pairs<time,arrival/departure>
* Now timings will be inserted in sorted order due to set property
* Iterate through the multiset
* If incoming timing is for arrival append the counter and decrease otherwise
* Return the maximum value of counter found

## Job Sequencing
https://practice.geeksforgeeks.org/problems/job-sequencing-problem-1587115620/1#

* Sort the array by profit
* Iterate through array
* If incoming job's deadline is within time take the job and increment time
* Return profit

## Fractional Knapsack
https://practice.geeksforgeeks.org/problems/fractional-knapsack-1587115620/1

* Sort the elements of array by value/weight ratio
* Start picking from start to end till weight is complete


