# Activities

## Task 1

- Refer to the following link. Discuss how the
  Recursive Factorial works:
  https://www.cs.usfca.edu/~galles/visualization/RecFact.html
- Refer to the following link. Discuss how the Recursive Fibonacci works:
  https://www.cs.usfca.edu/~galles/visualization/DPFib.html

## Task 2

There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs at a time. There is a simple implementations in `./src/` folder. Discuss how the code works.

Code counts the steps taken and also considers if 1 or 2 steps taken at a time.

## Task 3

- There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs or **3 stairs** at a time. Write a program that counts the number of ways, the person can reach the top. You can use the following program as a starter `./src/staircase1.cpp`. Also the link below might useful:
  https://www.includehelp.com/cpp-programs/stair-case-program-to-solve-the-staircase-problem.aspx

---

#include <stdio.h>

using namespace std;

int number_of_paths(int n) { if (n <= 0) return 0; if (n == 1) return 1; if (n == 2) return 2; if (n == 3) return 4;

return number_of_paths(n - 1) + number_of_paths(n - 2) + number_of_paths(n - 3);
}

int main() {

cout << "number of paths =  " << number_of_paths(4);
return 0;
}

## Task 4: Individual (at home)

- What are the pros/cons of recursive over iterative Programming?
- Difference between recursion and induction.

> Refer to the [links](#links) section below.

## Links

- https://cpp.sh/
- [Difference Between Recursion and Induction](https://www.geeksforgeeks.org/difference-between-recursion-and-induction/)
- [Recursion vs Iterative Programming](https://www.softwaretestinghelp.com/recursion-in-cpp/)
