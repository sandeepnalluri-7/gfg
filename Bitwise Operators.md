## 01. Bitwise Operators

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/bitwise-operators-1597314674--135255/1)

### Problem Description

**Task:** Given three positive integers a, b and c. Perform some bitwise operations on them as given below:1. d = a ^ a2. e = c ^ b3. f = a & b4. g = ~ eNote: ^ is for xor.Then print d e f g space seperately. Move the cursor to the next line after printing.Examples:Input: a = 1, b = 2, c = 3

#### Examples

##### Example 1

- **Output:**
```text
0 3 4 -4
```
- **Explanation:** We print d e f g after performing the given operations.

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(1)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (Python)

- **Submitted:** 2025-12-11 14:44:23
- **Status:** Correct
- **Marks:** 1

```python
def operators(a, b, c):
    #Do a^a below
    d=a^a
    #Do c^b below
    e=c^b
    #Do a&b below
    f=a&b
    #Do c|(a^a) below
    g=c|(a^a)
    #Do ~e below
    e=~e

    #The line below prints the output. Don't change it!
    print(d,e,f,g)
```

*Generated on: 11/28/2026, 6:52:34 PM*