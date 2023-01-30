# Activities

## Task 1

Refer to the first [link](#links).

- Why is Algorithm Analysis Important?

The accidental or unintentional use of an inefficient algorithm can significantly impact system performance.

- Explain the Big $O$ notation

Big O Notation is a tool used to describe the time complexity of algorithms.

- Compare `Linear`, `Logarithmic`, `Quadratic` and `Constant` complexities.

Name	        Big O
Constant	    O(c)
Linear	        O(n)
Quadratic	    O(n²)
Cubic	        O(n³)
Exponential	    O(2ⁿ)
Logarithmic	    O(log(n))
Log Linear	    O(nlog(n))

## Task2

Refer to the first [link](#links).

- Write a simple algorithm in C++ that finds the square of the first item in a list and then prints it on the screen.

#include <iostream>
#include <vector>

int main() {
  std::vector<int> list = {1, 2, 3, 4, 5};
  int result = list[0] * list[0];
  std::cout << result << std::endl;
  return 0;
}

- What is the complexity of the algorithm?

The complexity of the previous algorithm is O(1).

## Task 3

Refer to the first [link](#links).

- Write a simple program that displays all items in a list to the console.

#include <iostream>
#include <vector>

int main() {
  std::vector<int> numbers = {1, 2, 3, 4, 5};
  for (int number : numbers) {
    std::cout << number << std::endl;
  }
  return 0;
}

- What is the complexity of the algorithm?

The complexity of the previous algorithm is O(n), where n is the number of items in the list. This is because the algorithm loops through each item in the list once, and the time it takes to print each item is constant, so the total time taken is proportional to the number of items in the list.

## Task 4: : Individual, at home

Refer to this [pdf](./big_o.pdf):

- What is the difference between complexity and performance:
- Does complexity affects performance bor is it the other way around?
- Restate the formal definition of big $O$ in plain English

## Links

- [Big O Notation and Algorithm Analysis ](https://stackabuse.com/big-o-notation-and-algorithm-analysis-with-python-examples/)
- [Visualization](https://www.cs.usfca.edu/~galles/visualization/Search.html)
- [Big-O notation explained by a self-taught programmer](https://justin.abrah.ms/computer-science/big-o-notation-explained.html)
- [Big-O is easy to calculate, if you know how](https://justin.abrah.ms/computer-science/how-to-calculate-big-o.html)
- https://cpp.sh/
