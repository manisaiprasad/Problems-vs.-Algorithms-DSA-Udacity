# Problem 2: Search in a Rotated Sorted Array

The rotated array is able to be searched using a Binary Search Algorithm. My first method involved finding the pivot seperately but I later realized this was not necessary and the element could be found in one pass.

Time Complexity: O(log n)

Binary Search

Space Complexity: O(logn) solution is recursive and the call stack uses O(logn) space