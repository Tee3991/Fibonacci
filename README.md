# Fibonacci
## Using the "if" condition to manipulate the fibonacci of a number

def fibonacci(n):
    while n < 1:
        return 1
    else:
        return n + fibonacci(n - 1) 

fibonacci(7)
output: 29

def fibonacci(n):
  if n == 1 or n==2:
    return 1
  else:
    return n + fibonacci(n - 1) 

fibonacci(7)
output: 26
## Note: Although we are checking for the fibonacci of the same number but the output looks diffrent, which is as a result of the "if statement"
the if statement in the second program return 1 to for 2 making the aray [1,1,3,4,5,6,7]
