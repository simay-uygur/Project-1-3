# Project 1-3
Three projects that is on Patika Java Course.


## Project 1: SELECTION SORT

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




## Project 2: MERGE SORT

The processes of sorting the array [16,21,11,8,12,22] with Merge Sort are:

First dividing the array into two parts [16,21,1] and [8,12,22]
Then, [16,21], [1] and [8,12] ,[22].
Dividing again and that results in each array having one element then merging starts.
[16], [21], [1] and [8], [12], [22].
Then for the leftmost two arrays are compared (elements) and merged with accordingly. Because they were separeted lastly. Same for the 8 and 12. 
[16,21], [1] and [8,12], [22]
then compare and add to another array (for each two arrays separated with and). (merging)
[1,16,21] and [8,12,22]
Lastly one pair of array elements are compared and added to another new merged array.
Therefore, in the last, array is [1,8,16,21,22]. 

The Big-O notation for merge sort is (worst-case time complexity) O(nlogn). Because separating each array by two takes x times and 2^x = n. n represents the number of elements total in the array. Also merging process in each line of the tree (binary tree representing the process), we can observe that it takes linear time to comparing elements (the small arrays are sorted) therefore just one pass of each array is adequate.





## Project 3: BINARY TREE

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] given this array ,the processes of binary tree are:

Root is 7. 5 is less than the root, therefore it goes to the left of the 7. 
1 is less than 7 and 5, so it is placed on the left of 5.
8 is greater than 7 (root), so it goes to the right of 7. 
3 is less than 7 and 5 but greater than 1 therefore it is on the right of 1.
6 is greater than 5 less than 7, it goes to the right of 5. 9 is greater than 7 and 8, so it goes to the right of 8.
4 ia less than 6. It goes to the left of 6.
2 goes to the left of 3. 
Overall, tree structure is done.

The visualization:

        7
       / \
      5   8
     / \   \
    1   6   9
   / \  /
  0  3  4
     /
    2

