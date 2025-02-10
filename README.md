# RecursionError in Python Factorial Function

This repository demonstrates a common error in Python involving recursive functions and how to solve it.

The `factorial.py` file contains a recursive function to calculate factorials. This function works correctly for non-negative integers but causes a `RecursionError` when a negative integer is passed as input because it never hits the base case of n == 0. 

The `factorialSolution.py` file demonstrates a solution with error handling.