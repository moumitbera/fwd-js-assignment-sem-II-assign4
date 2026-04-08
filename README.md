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
