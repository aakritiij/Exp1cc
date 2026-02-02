Experiment 1: Competitive Coding

This repository contains solutions to three competitive coding problems implemented using Python. The focus is on clear logic, correctness, and efficient time complexity.

1. Contains Duplicate II

Language: Python

Logic:
I iterated through the array while storing the last index of each element in a dictionary. For every element, I checked whether it appeared before and whether the index difference was less than or equal to k. If both conditions were satisfied, I returned True. Otherwise, I updated the index and continued.

Time Complexity:
O(n)

2. Product of Array Except Self

Language: Python

Logic:
I first computed prefix products and stored them in the result array. Then, I traversed the array from the end to compute suffix products and multiplied them with the existing values in the result array. This allowed me to compute the required product for each index without using division.

Time Complexity:
O(n)

3. Median of Two Sorted Arrays

Language: Python

Logic:
I merged both sorted arrays into a single array and sorted it. I then checked whether the total number of elements was even or odd. For an odd length, I returned the middle element. For an even length, I returned the average of the two middle elements.

Time Complexity:
O(m + n)
