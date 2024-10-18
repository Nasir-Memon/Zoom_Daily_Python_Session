### **Exercise 1: Simple Functions**

Write a function `greet()` that takes no parameters and prints the message "Hello, welcome to Python functions!"

```python
# Defining the function
def greet():
    print("Hello, welcome to Python functions!")

# Calling the function
greet()
```

**Example Output:**
```
Hello, welcome to Python functions!
```

---

### **Exercise 2: Functions with Parameters**

Write a function `add_two_numbers(num1, num2)` that accepts two numbers as parameters, adds them, and prints the result.

```python
# Defining the function
def add_two_numbers(num1, num2):
    result = num1 + num2
    print(f"The sum of {num1} and {num2} is {result}")

# Example call
add_two_numbers(5, 10)
```

**Example Output:**
```
The sum of 5 and 10 is 15
```

---

### **Exercise 3: Return Values**

Write a function `square(number)` that takes a number as input and returns its square.

```python
# Defining the function
def square(number):
    return number ** 2

# Example call
result = square(4)
print(f"The square of 4 is {result}")
```

**Example Output:**
```
The square of 4 is 16
```

---

### **Exercise 4: Functions with Default Arguments**

Write a function `power(base, exponent=2)` that raises the base to the power of exponent. The exponent should default to 2 if not provided.

```python
# Defining the function
def power(base, exponent=2):
    return base ** exponent

# Example calls
print(f"3^2 = {power(3)}")     # Default exponent (2)
print(f"2^3 = {power(2, 3)}")  # Custom exponent (3)
```

**Example Output:**
```
3^2 = 9
2^3 = 8
```

---

### **Exercise 5: Keyword Arguments**

Write a function `introduce_person(name, age, city)` that prints a sentence like "My name is John, I'm 25 years old, and I live in New York."

```python
# Defining the function
def introduce_person(name, age, city):
    print(f"My name is {name}, I'm {age} years old, and I live in {city}.")

# Example call with keyword arguments
introduce_person(age=25, name="John", city="New York")
```

**Example Output:**
```
My name is John, I'm 25 years old, and I live in New York.
```

---

## **Assignment: Advanced Functions**

### **Problem 1: Find the Factorial**

Write a function `factorial(n)` that uses recursion to calculate the factorial of a given number `n`.

```python
# Defining the recursive function
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)

# Example call
print(f"Factorial of 5 is {factorial(5)}")
```

**Example Output:**
```
Factorial of 5 is 120
```

---

### **Problem 2: Prime Number Checker**

Write a function `is_prime(number)` that checks if a number is prime. Return `True` if it's prime and `False` otherwise.

```python
# Defining the function
def is_prime(number):
    if number < 2:
        return False
    for i in range(2, int(number**0.5) + 1):
        if number % i == 0:
            return False
    return True

# Example calls
print(f"7 is prime: {is_prime(7)}")
print(f"8 is prime: {is_prime(8)}")
```

**Example Output:**
```
7 is prime: True
8 is prime: False
```

---

### **Problem 3: Function with Variable-Length Arguments**

Write a function `find_average(*args)` that accepts a variable number of numeric arguments and returns their average.

```python
# Defining the function
def find_average(*args):
    if len(args) == 0:
        return 0
    return sum(args) / len(args)

# Example calls
print(f"Average of 4, 5, 6 is {find_average(4, 5, 6)}")
print(f"Average of 10, 20, 30, 40 is {find_average(10, 20, 30, 40)}")
```

**Example Output:**
```
Average of 4, 5, 6 is 5.0
Average of 10, 20, 30, 40 is 25.0
```

---

These examples should help you fully understand how to work with functions and parameters in Python for your **Day 3** session!