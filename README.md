# Project-1-3
Three projects that is on Patika Java Course.


## Project 1

This is the given array [22,27,16,2,18,6].
According to Selection sort, the steps are

From the first index (index zero) start searching for the least element. (2) swap it by 22. -> [2,27,16,22,18,6]
Then go to the second index and find the second least element. (the least element in the unsorted portion which is located at right) In this case it is 6. -> [2,6,16,22,18,27]
Then the least element is 16 but is in the correct position -> [2,6,16,22,18,27]
Then the least element is 18 -> [2,6,16,18,22,27] (22 and 18 swap positions)
Then nothing changes. 22 is the least then 27 is the least element.  


For the worst case, the array is reverse sorted (the least element is in the last position), every time algortihm sompares unsorted part's elements and find the least one. for one element (index) it does n, n-1 ,... comparisons. And there are n elements (indexes) Switching just takes O(1) time therefore the whole process is ***O(n^2)*** in the worst case.


When the array is sorted 18 has the *** Average Case. ***

According to the selection sort, the first 4 steps for sorting the array [7,3,5,8,2,9,4,15,6] are:

2 is the least element, swap with 7. --> [2,3,5,8,7,9,4,15,6]
3 is the least element, no swap. --> [2,3,5,8,7,9,4,15,6]
4 is the least element, swap with 5. --> [2,3,4,8,7,9,5,15,6]
5 is the least element, swap with 8. --> [2,3,4,5,7,9,8,15,6]




## Project 2









## Project 3

