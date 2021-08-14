# Trapping-Rain-Water
Given n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it can trap after raining.

to solve this problem we will do preprocessing . We will find max to the left and max to the right in two different array left and right array. Now we will take min(left[i],right[i])-arr[i]; we will sum up all these value that is our answer
