# 1237. Find Positive Integer Solution for a Given Equation

## Description

Given a callable function  `f(x, y)`  **with a hidden formula** and a value  `z` , reverse engineer the formula and return *all positive integer pairs * `x` * and * `y` * where * `f(x,y) == z` . You may return the pairs in any order.

While the exact formula is hidden, the function is monotonically increasing, i.e.:

	
-  `f(x, y)  f(1, 4) = 1 + 4 = 5.
x=2, y=3 -> f(2, 3) = 2 + 3 = 5.
x=3, y=2 -> f(3, 2) = 3 + 2 = 5.
x=4, y=1 -> f(4, 1) = 4 + 1 = 5.
```

**Example 2:**

```
Input: function_id = 2, z = 5
Output: [[1,5],[5,1]]
Explanation: The hidden formula for function_id = 2 is f(x, y) = x * y.
The following positive integer values of x and y make f(x, y) equal to 5:
x=1, y=5 -> f(1, 5) = 1 * 5 = 5.
x=5, y=1 -> f(5, 1) = 5 * 1 = 5.
```

 

**Constraints:**

	
-  `1 <= function_id <= 9` 
	
-  `1 <= z <= 100` 
	
- It is guaranteed that the solutions of  `f(x, y) == z`  will be in the range  `1 <= x, y <= 1000` .
	
- It is also guaranteed that  `f(x, y)`  will fit in 32 bit signed integer if  `1 <= x, y <= 1000` .
