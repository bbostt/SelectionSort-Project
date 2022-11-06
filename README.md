# Selection Sort

**[22,27,16,2,18,6]**

- ### Write the stages of the given array according to the sort type

  1. **[**2**,27,16,**22**,18,6]**
  2. [2,**6**,16,22,18,**27**]
  3. [2,6,**16**,22,18,27]
  4. [2,6,16,**18**,**22**,27]

- ### Write the Big-O Notation

  * The main time cost comes from scanning through the array to find the next smallest item. We do that n times. The first time, we'll be looking at n elements, the next time it'll be (n-1) elements, and so on, until we're left with just one element.

  * Adding all those up, we've got

    - n + (n - 1) + (n - 2) + . . . . . + 1

    - That's the triangular series, which is O(n²).

      

> Even if the input is already sorted, selection sort still involves scanning all the unsorted elements repeatedly to find the next-smallest. So, unlike insertion sort, it'll stay O(n²), even in the best case.

* ### After sorting the array, which case does the number 18 belong to ?

  * After sorting the array, the number 18 is in the middle of the array, so the number 18 is covered by the average case.
