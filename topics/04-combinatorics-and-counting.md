# Topic 4: Combinatorics and Counting

## 1. Introduction to Counting

Combinatorics is the branch of discrete mathematics that deals with counting arrangements, selections, and possibilities.

It is used in probability, scheduling, algorithm analysis, and computer science.

## 2. The Fundamental Principle of Counting

If there are m ways to do one task and n ways to do another, then there are m × n ways to do both.

Example:
A restaurant offers 3 drinks and 4 meals. Number of possible combinations = 3 × 4 = 12.

## 3. Permutations

A permutation is an arrangement of objects in a specific order.

The number of permutations of n distinct objects is:

n! = n × (n-1) × ... × 2 × 1

Example:
How many ways can 3 students stand in a line?
3! = 6

### Permutations of r objects from n

P(n,r) = n! / (n-r)!

This counts ordered selections.

## 4. Combinations

A combination is a selection of objects where order does not matter.

The number of combinations of r objects chosen from n is:

C(n,r) = n! / (r!(n-r)!)

Example:
Choose 2 students from 5: C(5,2) = 10.

## 5. Binomial Theorem

The binomial theorem expands powers of sums:

(a + b)^n = Σ C(n,k) a^(n-k) b^k

This connects algebra with combinatorics.

Example:
(a + b)^3 = a^3 + 3a^2b + 3ab^2 + b^3

## 6. Inclusion-Exclusion Principle

Used to count elements in unions of sets.

For two sets:
|A ∪ B| = |A| + |B| - |A ∩ B|

For more sets, you continue adding and subtracting intersections.

This is useful for counting overlaps in surveys and databases.

## 7. Pigeonhole Principle

If more items are placed into containers than there are containers, then at least one container has more than one item.

This simple idea is surprisingly powerful.

Example:
In any group of 13 people, at least two share a birth month because there are only 12 months.

## 8. Multinomial Coefficients

If you want to divide n objects into groups of sizes n1, n2, ..., nk, then the number of ways is:

n! / (n1! n2! ... nk!)

This generalizes combinations.

## 9. Applications

Combinatorics is used in:
- probability calculations
- algorithm design
- scheduling and optimization
- coding theory
- cryptography
- computer networking

## 10. Summary

Combinatorics teaches us how to count carefully and systematically. The key tools are the multiplication rule, permutations, combinations, inclusion-exclusion, and the pigeonhole principle. These ideas are fundamental to both mathematics and computer science.
