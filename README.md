# Day-07

## arrayTimeComplexity.m ##

This code demonstrates two search methods for finding a number (index = 998) in an array a = 1:1000.

### 1. Linear Search (First Part):
   
Loop from start to end of the array.

Compares each element to the target (998).

If found, prints the index and stops.

Uses tic/toc to measure execution time.

### 2. Binary Search (Second Part):
   
More efficient search using divide-and-conquer.

Calculates middle of the array.

If mid value equals target, it prints the index.

Otherwise, narrows the search range (startPoint, endPoint).

Also uses tic/toc to measure time.

![timeComplexity](https://github.com/user-attachments/assets/fc6286b4-713c-434d-8887-6ab6e7d148bb)

## selectionSort.m ##

This code implements the Selection Sort algorithm to sort an array in ascending order.



How It Works:
For each position i in the array:

Assume arr(i) is the smallest (minIndex = i).

Search the rest of the array (j = i+1 to n) to find the actual smallest element.

Swap it with arr(i) using a temporary variable temp.

Repeat for all positions until the array is sorted.

![selectionSort](https://github.com/user-attachments/assets/60c6a95a-bf7d-4e3b-8f55-a7f16371d5ee)



