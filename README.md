# priyaaa
def find_factorial(n):
    if n < 0:
        return "Factorial does not exist for negative numbers."
    
    factorial = 1
    # Loop from 1 to n (n + 1 is exclusive)
    for i in range(1, n + 1):
        factorial *= i
        
    return factorial

# Example usage:
num = 5
print(f"The factorial of {num} is {find_factorial(num)}")


