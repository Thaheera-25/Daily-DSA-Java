# Running Sum of Array

## Problem
Given an array `nums`, return the running sum where  
runningSum[i] = sum(nums[0] … nums[i])

## Code
class Solution {
    public int[] runningSum(int[] nums) {
        int[] result = new int[nums.length];
        result[0] = nums[0];

        for (int i = 1; i < nums.length; i++) {
            result[i] = result[i - 1] + nums[i];
        }
        return result;
    }
}


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
