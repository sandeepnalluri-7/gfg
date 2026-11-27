## 01. Last Digit of Number

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/last-digit-of-a-number--145429/1)

### Problem Description

**Task:** Given an integer n. Write a program to print the last digit of n.

#### Examples

##### Example 1

- **Input:**
```text
n = 10
```
- **Output:**
```text
0
```

##### Example 2

- **Input:**
```text
n = 9768
```
- **Output:**
```text
8
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (Java)

- **Submitted:** 2026-11-27 21:07:08
- **Status:** Correct
- **Marks:** 1

```java
import java.util.*;

class GFG {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();

        // code here
        System.out.print(Math.abs(n%10));
    }
}
```

*Generated on: 11/27/2026, 9:07:30 PM*