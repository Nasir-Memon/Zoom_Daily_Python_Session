Here’s an assignment for **Day 2: Nested Loops and Loop Control (break, continue)** to reinforce your understanding:

---

## **Day 2 Assignment: Nested Loops and Loop Control**

### **Instructions:**
Complete the following exercises using nested loops and loop control mechanisms like `break` and `continue`. Write Python functions for each task and include comments to explain your logic.

---

### **1. Pyramid of Stars**
Write a function `pyramid(n)` that prints a pyramid of stars (`*`) with `n` rows.

**Example:**
For `n = 5`, the output should be:
```
    *
   ***
  *****
 *******
*********
```

---

### **2. Find and Print Prime Numbers in a Range**
Write a function `print_primes(start, end)` that prints all prime numbers between `start` and `end` using nested loops.

**Example:**
For `start = 10` and `end = 30`, the output should be:
```
11
13
17
19
23
29
```

---

### **3. Skip Multiples of a Number**
Write a function `skip_multiples(n, x)` that prints numbers from 1 to `n`, but skips any multiples of `x`.

**Example:**
For `n = 20` and `x = 4`, the output should be:
```
1 2 3 5 6 7 9 10 11 13 14 15 17 18 19
```

---

### **4. Create a Multiplication Table (with Conditions)**
Write a function `multiplication_table(n)` that prints a multiplication table up to `n`, but skips all multiples of 5 and stops printing a row if the product exceeds 50.

**Example:**
For `n = 10`, part of the output should look like this:
```
1  2  3  4     6  7  8  9  10
2  4  6  8     12 14 16 18 20
3  6  9 12     18 21 24 27 30
...
```

---

### **5. Print a Hollow Square of Stars**
Write a function `hollow_square(n)` that prints a hollow square of stars with side length `n`. The edges should be made of stars (`*`), and the inside should be empty spaces.

**Example:**
For `n = 5`, the output should be:
```
*****
*   *
*   *
*   *
*****
```

---

### **6. Pattern with Numbers**
Write a function `number_pattern(n)` that prints a pattern where each row starts with the row number and counts backward to 1.

**Example:**
For `n = 5`, the output should be:
```
1
2 1
3 2 1
4 3 2 1
5 4 3 2 1
```

---

### **7. Search for a Target in a 2D Matrix**
Given a 2D list (matrix), write a function `find_in_matrix(matrix, target)` that searches for a `target` value. If found, print the position (row, column). Use `break` to exit the search once the target is found.

**Example:**
For the matrix:
```
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
```
Calling `find_in_matrix(matrix, 5)` should print:
``