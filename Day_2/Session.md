Here are 8 exercise examples for Day 2: Nested Loops and Loop Control (break, continue):

1. Print a 5x5 Grid of Stars

Use a nested loop to print a 5x5 grid of stars (*).

for i in range(5):
    for j in range(5):
        print('*', end=' ')
    print()

Exercise: Modify the code to print a 4x6 grid of stars.


---

2. Multiplication Table

Write a nested loop that prints the multiplication table (from 1x1 to 10x10).

for i in range(1, 11):
    for j in range(1, 11):
        print(i * j, end='\t')
    print()

Exercise: Create a multiplication table up to 12x12.


---

3. Triangle of Numbers

Print a triangle of numbers where each row has as many numbers as the row number.

for i in range(1, 6):
    for j in range(1, i + 1):
        print(j, end=' ')
    print()

Exercise: Modify the code to print the reverse triangle starting from 5 down to 1.


---

4. Break in a Nested Loop

Create a nested loop where the inner loop breaks when a certain condition is met.

for i in range(1, 6):
    for j in range(1, 6):
        if j == 3:
            break
        print(f"i={i}, j={j}")

Exercise: Test how break affects the inner loop when j == 3.


---

5. Continue in a Nested Loop

Use continue to skip a specific iteration in the inner loop.

for i in range(1, 6):
    for j in range(1, 6):
        if j == 3:
            continue
        print(f"i={i}, j={j}")

Exercise: Experiment with continue to skip j == 3 and observe the output.


---

6. Find Prime Numbers

Write a program to find all prime numbers between 1 and 50 using nested loops.

for num in range(2, 51):
    is_prime = True
    for i in range(2, num):
        if num % i == 0:
            is_prime = False
            break
    if is_prime:
        print(num)

Exercise: Modify the program to find prime numbers between 1 and 100.


---

7. Pattern with Break

Print a pattern of numbers but stop the loop early when a condition is met.

for i in range(1, 6):
    for j in range(1, 6):
        print(j, end=' ')
        if j == i:
            break
    print()

Exercise: Analyze how break controls the pattern output.


---

8. Multiplication Table with Skipping

Print a multiplication table but skip all multiples of 3 using continue.

for i in range(1, 11):
    for j in range(1, 11):
        if (i * j) % 3 == 0:
            continue
        print(i * j, end='\t')
    print()

Exercise: Modify the code to skip multiples of 5.