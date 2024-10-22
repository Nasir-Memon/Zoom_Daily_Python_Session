#1st Example 

def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)


#2nd Example 

def countdown(n):
    if n <= 0:  
        print("Liftoff!")
    else:
        print(n)
        countdown(n - 1)  
countdown(5)

#3rd Example 

def sum_natural(n):
    if n <= 0:  
        return 0
    else:
        return n + sum_natural(n - 1)  # Recursive call
print(sum_natural(5))

#4th Example 

def reverse_string(s):
    if len(s) == 0:  
        return s
    else:
        return s[-1] + reverse_string(s[:-1])  # Recursive call
print(reverse_string("hello"))

#5th Example 

def power(x, n):
    if n == 0:  # Base case
        return 1
    else:
        return x * power(x, n - 1)  # Recursive call

print(power(2, 4)) 





