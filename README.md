# Testing
# Solution to a System of Linear Equations

## Aim:
To write a Python program to find the solution to a system of linear equations.

## Equipment Required:
- **Hardware:** PC
- **Software:** Anaconda (Python 3.7 Installation) or equivalent IDE

## Algorithm:
1. Import the `numpy` module to utilize built-in functions for calculations.
2. Prepare the coefficient matrix and constant matrix from the given equations using `np.array()`.
3. Use `np.linalg.solve()` to find the solution to the system of equations.
4. Output the solution.

## Program:
The following Python program demonstrates how to solve a system of linear equations:

```python
import numpy as np

# Coefficient matrix
a = np.array([[5, -3, -10], [2, 2, -3], [-3, -1, 5]])

# Constant matrix
b = np.array([-9, 4, -1])

# Solving the system of equations
solution = np.linalg.solve(a, b)

# Printing the solution
print(solution)
![images](https://github.com/user-attachments/assets/75243114-3b34-45c9-8443-7b2a8556c32b)
