# 1145. Binary Tree Coloring Game

## Description

Two players play a turn based game on a binary tree. We are given the  `root`  of this binary tree, and the number of nodes  `n`  in the tree.  `n`  is odd, and each node has a distinct value from  `1`  to  `n` .

Initially, the first player names a value  `x`  with  `1 

```
Input: root = [1,2,3,4,5,6,7,8,9,10,11], n = 11, x = 3
Output: true
Explanation: The second player can choose the node with value 2.
```

**Example 2:**

```
Input: root = [1,2,3], n = 3, x = 1
Output: false
```

 

**Constraints:**

	
- The number of nodes in the tree is  `n` .
	
-  `1 <= x <= n <= 100` 
	
-  `n`  is odd.
	
- 1 <= Node.val <= n
	
- All the values of the tree are **unique**.
