## 01. Swap Two Numbers

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/swap-the-numbers/1)

### Problem Description

**Task:** Given two numbers a and b, you need to swap their values so a holds the value of b and b holds the value of a.Examples :Input: a = 1 b = 2

#### Examples

##### Example 1

- **Output:**
```text
2 1
```
- **Explanation:** Initially a = 1 and b = 2, now a = 2 and b = 1.

##### Example 2

- **Input:**
```text
a = 6 b = 7 Output: 7 6
```
- **Explanation:** Initially a = 6 and b = 7, now a = 7 and b = 6.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (2)

#### Solution 1 (Java)

- **Submitted:** 2026-11-25 19:26:46
- **Status:** Correct
- **Marks:** 0

```java
import java.util.Scanner;

class GFG {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();

        // code here
        a=a+b;
        b=a-b;
        a=a-b;

        System.out.print(a + " " + b);
    }
}
```

#### Solution 2 (Java)

- **Submitted:** 2025-12-11 14:37:28
- **Status:** Correct
- **Marks:** 1

```java
a = int(input())
b = int(input())
a=a+b
b=a-b
a=a-b
print(a,b)
```

*Generated on: 11/25/2026, 7:26:57 PM*