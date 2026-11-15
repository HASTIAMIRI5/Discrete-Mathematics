# Questions: Logic and Proof Techniques

## Question 1
Construct a truth table for p ∧ q.

### Solution
| p | q | p ∧ q |
|---|---|------|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |

## Question 2
Prove by contrapositive: If n^2 is even, then n is even.

### Solution
The contrapositive is: If n is odd, then n^2 is odd. Let n = 2k + 1. Then n^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1, which is odd. Therefore the original statement is true.

## Question 3
Use mathematical induction to prove 1 + 2 + ... + n = n(n+1)/2.

### Solution
Base case: n=1 gives 1 = 1(2)/2 = 1.
Inductive step: assume true for n = k. Then
1 + ... + k + (k+1) = k(k+1)/2 + (k+1) = (k+1)(k+2)/2.
So the formula holds for k+1.

## Question 4
Write the negation of ∀x (x > 2 → x > 1).

### Solution
∃x such that ¬(x > 2 → x > 1)
This is equivalent to ∃x (x > 2 ∧ x ≤ 1).

## Question 5
Determine whether the statement "If it rains, then the ground is wet" is logically equivalent to "If the ground is not wet, then it does not rain."

### Solution
Yes. This is the contrapositive and is logically equivalent.
