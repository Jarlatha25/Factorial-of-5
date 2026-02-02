# Factorial-of-5
def fact(n):
    if n == 1:
        f = 1
    else:
        f = n * fact(n-1)
    return f

num = int(input("Enter an integer: "))
result = fact(num)
print("The factorial of", num, "is:", result)
Sample Input:
Copy code

Enter an integer: 5
Output:
Copy code

The factorial of 5 is: 120
