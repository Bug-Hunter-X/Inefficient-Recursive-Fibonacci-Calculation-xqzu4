# Inefficient Recursive Fibonacci
This repository demonstrates a common coding error in recursive functions: redundant calculations leading to exponential time complexity. The `bug.py` file contains the inefficient recursive implementation of the Fibonacci sequence.  The `bugSolution.py` file provides an optimized solution using dynamic programming to avoid redundant calculations.

## How to run
1. Clone the repository.
2. Navigate to the directory in your terminal.
3. Run the Python scripts using `python bug.py` and `python bugSolution.py`.  Compare their execution times for larger input values.

## Optimization
The inefficient implementation suffers from repeated calculations. For example, calculating `fibonacci(5)` involves recalculating `fibonacci(3)` and `fibonacci(2)`, and so on.  Dynamic programming addresses this by storing previously computed values, avoiding redundant work.