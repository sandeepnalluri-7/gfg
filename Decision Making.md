## 01. Decision Making

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/decision-making/1)

### Problem Description

**Task:** Given two integers, n and m. The task is to check the relation between n and m. Print "less" if n < m, "equal" if n = = m, and "greater" if n > m.Examples : Input: n = 4, m = 8

#### Examples

##### Example 1

- **Output:**
```text
greater
```
- **Explanation:** 8 > 4 so print 'greater'.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (Java)

- **Submitted:** 2026-11-24 20:27:18
- **Status:** Correct
- **Marks:** 1

```java
import java.util.Scanner;

class GFG {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int m = sc.nextInt();

        // code here
        if(n<m){
            System.out.print("less");
        }
        else if(n==m){
            System.out.print("equal");
        }
        else{
            System.out.print("greater");
        }
    }
}
```

*Generated on: 11/24/2026, 8:27:31 PM*