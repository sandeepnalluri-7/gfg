## 01. Print GFG n times

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/print-gfg-n-times/1)

### Problem Description

**Task:** Given a positive number n, print the string "GFG" exactly n times separated by a single space.Examples:Input: n = 5

#### Examples

##### Example 1

- **Output:**
```text
GFG GFG GFGExplanation: The string "GFG" is printed 3 times separated by spaces.
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (Java)

- **Submitted:** 2026-11-27 21:10:40
- **Status:** Correct
- **Marks:** 1

```java
class Solution {
    void printGfg(int n) {
        // code here
        for(int i=0;i<n;i++){
            System.out.print("GFG ");
        }
    }
}
```

*Generated on: 11/27/2026, 9:10:53 PM*