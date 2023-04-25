# Selection-sorting

The smallest (or largest) element from the unsorted part of the list is repeatedly chosen and moved to the sorted part of the list using a simple and effective sorting algorithm known as selection sort.  The algorithm repeatedly chooses the smallest (or largest) element from the list's unsorted section and switches it with the unsorted section's initial member. Up until the complete list is sorted, this procedure is repeated for the last unsorted section of the list. A selection sort variant known as "Bidirectional selection sort" alternates between the smallest and largest elements in the list of elements, which can sometimes make the algorithm run more quickly.

The algorithm maintains two subarrays in a given array.

1. The already-sorted subarray.
2. Unsorted subarrays made up the remainder.


The least entry (regarding ascending order) from the unsorted subarray is chosen and relocated to the start of the sorted subarray in each iteration of the selection sort.

The size of the sorted subarray increases after each iteration while the size of the unsorted subarray decreases.

![234088023-36b93c8a-17e6-474e-8b8a-8cacfbdb9671](https://user-images.githubusercontent.com/125882453/234397173-4852373a-8d79-4396-a521-5f4cea6b8523.png)


Advantages of Selection Sort Algorithm:

1. Simple and easy to understand.
2. Preserves the relative order of items with equal keys which means it is stable.
3. Works well with small datasets.
4. It is adaptable to various types of data types.
5. Selection sort is an in-place sorting algorithm, which means it does not require any additional memory to sort the list.

Disadvantages of the Selection Sort Algorithm:

1. Selection sort has a time complexity of O(n^2) in the worst and average case.
2. Does not work well on large datasets.
3. The selection sort algorithm needs to iterate over the list multiple times, thus it can lead to an unbalanced branch.
4. Selection sort has poor cache performance and hence it is not cache friendly.
5. Not adaptive, meaning it doesn’t take advantage of the fact that the list may already be sorted or partially sorted
