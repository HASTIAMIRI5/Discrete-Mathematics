# Topic 1: Sets and Functions

## 1. Introduction to Sets

A set is a collection of distinct objects. The objects inside a set are called elements or members.

Example:
- A = {1, 2, 3, 4}
- B = {a, e, i, o, u}

Sets can contain numbers, letters, symbols, or even other sets. The order of elements does not matter, and duplicates are not counted separately.

### Important notation
- a ∈ A means "a is an element of A"
- a ∉ A means "a is not an element of A"
- ∅ represents the empty set
- |A| means the cardinality (number of elements) of A

### Examples
- If A = {2, 4, 6}, then 2 ∈ A and 5 ∉ A.
- If B = {x | x is an even number less than 10}, then B = {2, 4, 6, 8}.

## 2. Set Operations

### Union
A ∪ B contains all elements that are in A or B.

Example:
A = {1, 2, 3}
B = {2, 3, 4}
A ∪ B = {1, 2, 3, 4}

### Intersection
A ∩ B contains elements common to both sets.

A ∩ B = {2, 3}

### Difference
A - B contains elements in A but not in B.

A - B = {1}

### Complement
The complement of A, usually written A^c or A', contains all elements in the universal set U that are not in A.

If U = {1, 2, 3, 4, 5} and A = {1, 3, 5}, then A^c = {2, 4}.

## 3. Subsets

A set A is a subset of B if every element of A is also in B.

A ⊆ B

Example:
A = {1, 2}
B = {1, 2, 3}
Then A ⊆ B.

### Proper subset
A is a proper subset of B if A ⊆ B and A ≠ B.

## 4. Power Set

The power set of A is the set of all subsets of A.

If A = {1, 2}, then
P(A) = {∅, {1}, {2}, {1,2}}

If |A| = n, then |P(A)| = 2^n.

## 5. Cartesian Product

The Cartesian product A × B is the set of all ordered pairs (a, b) where a ∈ A and b ∈ B.

Example:
A = {1,2}
B = {x,y}
A × B = {(1,x), (1,y), (2,x), (2,y)}

This is important in relations, functions, and databases.

## 6. Functions

A function f from set A to set B is a rule that assigns each element of A exactly one element in B.

Notation:
f: A → B

### Domain and codomain
- Domain: the set A
- Codomain: the set B
- Range: the set of actual outputs produced by the function

Example:
f(x) = x^2
Domain: all real numbers
Codomain: all real numbers
Range: all nonnegative real numbers

## 7. Types of Functions

### One-to-one (injective)
No two different inputs have the same output.

If f(a) = f(b), then a = b.

### Onto (surjective)
Every element of the codomain is hit by at least one input.

### Bijective
A function that is both one-to-one and onto.

Bijective functions are invertible.

## 8. Composition of Functions

If f: A → B and g: B → C, then the composition g ∘ f: A → C is defined by
(g ∘ f)(x) = g(f(x))

This is a foundational concept in computer science, algebra, and logic.

## 9. Why Sets and Functions Matter

Sets and functions are essential because they give structure to mathematical reasoning. They are used to define:
- relations
- sequences
- data types
- algorithms
- graphs
- databases
- formal proofs

In discrete mathematics, nearly every topic stands on this foundation.

## 10. Summary

A set is a collection of elements, and set operations help us build more complex structures. Functions describe relationships between sets. Understanding these ideas is vital because they appear in logic, number theory, combinatorics, and graph theory.

Key ideas:
- union, intersection, difference, complement
- subsets and power sets
- ordered pairs and Cartesian products
- domain, codomain, and range
- injective, surjective, and bijective functions
