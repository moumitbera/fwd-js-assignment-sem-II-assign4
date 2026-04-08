# FWD ASSIGNMENT 04
## Question 01: 
Time Complexity O(n).

Loop through each number (x) in [L, R] and check: 
1. Divisibility check x must be divisible by k.
2. Digit Sum Check.
3. Check if the computed digit sum is a prime number
4. X must not contain any zero (Zero Check)
If valid increment count number.

## Question 02: 
Time complexity: effectively O(1) constant (3 times)

We run the loop 3 times, and follow the rules for everytime based on if curr is even or odd. 
We finally after 3 loops, verify the middle digit == seed. 
And output as such.

## Question 03:
Time Complexity: O(N)

Check two conditions:
check_num is a palindrome
check_num is divisible by k
As soon as both conditions are satisfied, return the current x.

The function returns the smallest non-negative integer x such that:
n + x is a palindrome
n + x is divisible by k
If no such value is found within the limit, return -1

## Question 04: 
Time Complexity: O(1)
Just follow the instructions in the pdf. 

## Question 05:
Time Complexity: O(N)

Take inputs n and seed
Compute cs = seed + 2
Initialize sum = 0
Start iterating from m = 1 upwards
For each m, add it to sum only if it is not divisible by cs
Continue until sum ≥ n
Once reached, output the current value of m and the accumulated sum

## Question 06:
Time Complexity: O(1)

Compute initial score with formula given
If score becomes negative, set it to 0
If total attempts (a + b + c) > 50, subtract 10 marks
If score >= 60 : PASS
Otherwise: FAIL
Display final score along with result
