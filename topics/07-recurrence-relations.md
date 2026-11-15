# Topic 7: Recurrence Relations

## 1. What Is a Recurrence Relation?

A recurrence relation defines a sequence by relating each term to earlier terms.

Example:
T(n) = T(n-1) + 2
with T(1) = 3

This means each term is 2 more than the previous one.

## 2. Linear Recurrence Relations

A linear recurrence has the form:

a_n = c_1 a_{n-1} + c_2 a_{n-2} + ... + c_k a_{n-k} + f(n)

If f(n) = 0, the recurrence is homogeneous.

## 3. Example: Fibonacci Sequence

F(0) = 0, F(1) = 1
F(n) = F(n-1) + F(n-2) for n ≥ 2

This produces:
0, 1, 1, 2, 3, 5, 8, 13, ...

The Fibonacci sequence appears in nature, algorithms, and growth models.

## 4. Solving Recurrence Relations

There are several standard methods:
- iteration
- characteristic equation
- generating functions (more advanced)

### Example: arithmetic sequence
a_n = a_{n-1} + d

This gives:
 a_n = a_0 + nd

### Example: geometric sequence
a_n = r a_{n-1}

This gives:
 a_n = a_0 r^n

## 5. Characteristic Equation Method

For a homogeneous linear recurrence with constant coefficients, assume a solution of the form r^n.

Example:
a_n = 3a_{n-1} + 4a_{n-2}

Characteristic equation:
 r^2 = 3r + 4
 r^2 - 3r - 4 = 0
(r - 4)(r + 1) = 0

So the general solution is:
 a_n = A(4^n) + B((-1)^n)

## 6. Initial Conditions

Initial conditions determine the constants A and B.

Without initial conditions, the solution is general.

With them, we can find exact values.

## 7. Recurrence Relations in Algorithms

Recurrence relations are essential for analyzing algorithm running time.

Example:
T(n) = 2T(n/2) + n

This recurrence describes divide-and-conquer algorithms such as merge sort.

## 8. Why This Topic Matters

Recurrences describe processes that build on previous values. They are indispensable in:
- algorithm analysis
- dynamic programming
- finance and population models
- computer science theory

## 9. Summary

Recurrence relations model sequences where each term depends on earlier ones. Mastering them allows us to solve problems in algorithm analysis, mathematics, and computing.
