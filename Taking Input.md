## 01. Taking Input

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/taking-input/1)

### Problem Description

**Task:** You need to perform three separate tasks based on the given input:
String Input and Print: Read a string s (which may contain spaces) and print it as it is.
Integer Input and Print: Read an integer n and print it without any change.
Float Input and floor Print: Read a floating-point number as input, take its floor value, and print as an integer.

#### Examples

##### Example 1

- **Input:**
```text
s = "Hello", n = 20, f = 5.5Output: Hello 20 5Explanation: The string Hello is printed as it is. The integer 20 is printed without any change.For floating-point number 5.5, its floor value 5 is printed.
```

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (5)

#### Solution 1 (Java)

- **Submitted:** 2026-11-22 17:43:34
- **Status:** Correct
- **Marks:** 0

```java
import java.util.Scanner;

class GFG {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        String s=sc.nextLine();
        int n=sc.nextInt();
        float f=sc.nextFloat();
        int ff=(int)(f); // To Store floor of float variable f

        // code here
        

        System.out.println(s);
        System.out.println(n);
        System.out.println(ff);
    }
}
```

#### Solution 2 (Java)

- **Submitted:** 2025-12-11 12:03:08
- **Status:** Correct
- **Marks:** 1

```java
n=int(input())
print(n+10)
```

#### Solution 3 (Java)

- **Submitted:** 2025-12-11 12:01:51
- **Status:** Correct
- **Marks:** 1

```java
s=input()
print(s)
```

#### Solution 4 (Java)

- **Submitted:** 2025-12-11 12:00:21
- **Status:** Correct
- **Marks:** 1

```java
f=float(input())
print(f*10)
```

#### Solution 5 (Java)

- **Submitted:** 2025-12-11 11:43:53
- **Status:** Correct
- **Marks:** 2

```java
s=str(input())
print(s)
i=int(input())
print(i+10)
f=float(input())
print(f*10)
```

*Generated on: 11/22/2026, 5:43:59 PM*