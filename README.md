# Median-of-2-Sorted-Arrays-of-Same-Sizes

## Difficulty: Hard
Given two sorted arrays array1 and array2 of same sizes. Find the median of the two sorted arrays.

Example 1:

Input:
n = 5
array1[] = {1, 12, 15, 26, 38}
array2[] = {2, 13, 17, 30, 45}
Output: 16
Explanation: The merged sorted array is {1, 2, 12, 13, 15, 17, 26, 30, 38, 45}. The middle two elements are 15 and 17, so median = (15 + 17)/2 = 16

Example 2:

Input:
n = 1
array1[] = {10}
array2[] = {21}
Output: 15.5
Explanation : The merged sorted array is {10, 21}. The middle two elements are 10 and 21, so median = (10 + 21)/2 = 15.5

Your Task:
The task is to complete the function MedianOfArrays() that takes array1 and array2 as input and returns their median. 

Can you solve the problem in expected time complexity?

Expected Time Complexity: O(log n).
Expected Auxiliary Space: O(1).
