# Running Sum of Array

## Problem
Given an array `nums`, return the running sum where  
runningSum[i] = sum(nums[0] … nums[i])

## Example
Input: [1,2,3,4]  
Output: [1,3,6,10]

## Approach
- Initialize first element as nums[0]
- For each index i, add current element with previous sum
- Store results in a new array

## Time Complexity
O(n)

## Space Complexity
O(n)

## Language
Java
