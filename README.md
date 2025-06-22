# Financial Forecasting - Recursive Approach

## 1. Understanding Recursive Algorithms
Recursion simplifies problems by solving smaller instances of the same problem.
E.g., factorial, Fibonacci, and growth computations.

## 2. Setup
Future Value (FV) is calculated recursively using:
FV = PV * (1 + r)^n

## 3. Implementation
Java method recursively multiplies current value by (1 + rate) until years reach 0.

## 4. Time Complexity
- Time: O(n)
- Space: O(n) due to call stack

## 5. Optimization
- Use iteration for large inputs.
- Apply memoization if repeated calls happen with the same input.
