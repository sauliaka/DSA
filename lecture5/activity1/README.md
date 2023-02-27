# Activities

## Task 1

- Refer to the following link. Discuss how the
  Recursive Factorial works:
  https://www.cs.usfca.edu/~galles/visualization/RecFact.html

---
Recursive factorial is a function that calculates the factorial of a given number using a recursive approach. The factorial of a positive integer n is defined as the product of all positive integers up to and including n. For example, the factorial of 5 (written as 5!) is calculated as follows:

5! = 5 x 4 x 3 x 2 x 1 = 120

Here's how the recursive factorial works:

The function takes a positive integer n as input.

If n is equal to 1, the function returns 1 (base case).

If n is greater than 1, the function calls itself recursively with n-1 as the argument and multiplies the result by n.

The recursion continues until the base case is reached, at which point the function returns the final result.


- Refer to the following link. Discuss how the Recursive Fibonacci works:
  https://www.cs.usfca.edu/~galles/visualization/DPFib.html

---

Recursive Fibonacci is a function that calculates the nth Fibonacci number using a recursive approach. The Fibonacci sequence is a series of numbers in which each number is the sum of the two preceding numbers. The first two numbers in the sequence are 0 and 1. For example, the first ten Fibonacci numbers are:

0, 1, 1, 2, 3, 5, 8, 13, 21, 34

Here's how the recursive Fibonacci works:

The function takes a positive integer n as input.

If n is equal to 0 or 1, the function returns n (base cases).

If n is greater than 1, the function calls itself recursively with n-1 and n-2 as the arguments and adds the results.

The recursion continues until the base case is reached, at which point the function returns the final result.

## Task 2

There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs at a time. There is a simple implementations in `./src/` folder. Discuss how the code works.

Code counts the steps taken and also considers if 1 or 2 steps taken at a time.

## Task 3

- There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs or **3 stairs** at a time. Write a program that counts the number of ways, the person can reach the top. You can use the following program as a starter `./src/staircase1.cpp`. Also the link below might useful:
  https://www.includehelp.com/cpp-programs/stair-case-program-to-solve-the-staircase-problem.aspx

---
```cpp
#include <iostream>

using namespace std;

int number_of_paths(int n) { 
  if (n <= 0) return 0; 
  if (n == 1) return 1; 
  if (n == 2) return 2; 
  if (n == 3) return 4;

return number_of_paths(n - 1) + number_of_paths(n - 2) + number_of_paths(n - 3);
}

int main() {

cout << "number of paths =  " << number_of_paths(4);
return 0;
}
```

## Task 4: Individual (at home)

- What are the pros/cons of recursive over iterative Programming?
- Difference between recursion and induction.

> Refer to the [links](#links) section below.

## Links

- https://cpp.sh/
- [Difference Between Recursion and Induction](https://www.geeksforgeeks.org/difference-between-recursion-and-induction/)
- [Recursion vs Iterative Programming](https://www.softwaretestinghelp.com/recursion-in-cpp/)
