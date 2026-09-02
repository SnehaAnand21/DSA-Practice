# 2856. Minimum Array Length After Pair Removals

## Description

Given an integer array  `num`  sorted in non-decreasing order.

You can perform the following operation any number of times:

	
- Choose **two** indices,  `i`  and  `j` , where  `nums[i] 

**Input:** nums = [1,2,3,4]

**Output:** 0

**Explanation:**

**Example 2:**

**Input:** nums = [1,1,2,2,3,3]

**Output:** 0

**Explanation:**

**Example 3:**

**Input:** nums = [1000000000,1000000000]

**Output:** 2

**Explanation:**

Since both numbers are equal, they cannot be removed.

**Example 4:**

**Input:** nums = [2,3,4,4,4]

**Output:** 1

**Explanation:**

 

**Constraints:**

	
-  `1 <= nums.length <= 105` 
	
-  `1 <= nums[i] <= 109` 
	
-  `nums`  is sorted in **non-decreasing** order.
