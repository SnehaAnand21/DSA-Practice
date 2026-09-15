# 3244. Shortest Distance After Road Addition Queries II

## Description

You are given an integer  `n`  and a 2D integer array  `queries` .

There are  `n`  cities numbered from  `0`  to  `n - 1` . Initially, there is a **unidirectional** road from city  `i`  to city  `i + 1`  for all  `0 

**Input:** n = 5, queries = [[2,4],[0,2],[0,4]]

**Output:** [3,2,1]

**Explanation: **

After the addition of the road from 2 to 4, the length of the shortest path from 0 to 4 is 3.

After the addition of the road from 0 to 2, the length of the shortest path from 0 to 4 is 2.

After the addition of the road from 0 to 4, the length of the shortest path from 0 to 4 is 1.

**Example 2:**

**Input:** n = 4, queries = [[0,3],[0,2]]

**Output:** [1,1]

**Explanation:**

After the addition of the road from 0 to 3, the length of the shortest path from 0 to 3 is 1.

After the addition of the road from 0 to 2, the length of the shortest path remains 1.

 

**Constraints:**

	
-  `3 <= n <= 105` 
	
-  `1 <= queries.length <= 105` 
	
-  `queries[i].length == 2` 
	
-  `0 <= queries[i][0] < queries[i][1] < n` 
	
-  `1 < queries[i][1] - queries[i][0]` 
	
- There are no repeated roads among the queries.
	
- There are no two queries such that  `i != j`  and  `queries[i][0] < queries[j][0] < queries[i][1] < queries[j][1]` .
