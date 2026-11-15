# Topic 2: Logic and Proof Techniques

## 1. Propositional Logic

A proposition is a statement that is either true or false, but not both.

Examples:
- "2 + 2 = 4" is true.
- "The sky is green" is false.
- "x + 1 = 5" is not a proposition unless x is specified.

### Logical connectives
- ¬ (not)
- ∧ (and)
- ∨ (or)
- → (implies)
- ↔ (if and only if)

## 2. Truth Tables

A truth table lists all possible truth values of logical statements.

For example, for p ∧ q:
- if p = T and q = T, result = T
- otherwise result = F

For p → q: it is false only when p is true and q is false.

## 3. Logical Equivalences

Two expressions are logically equivalent if they have the same truth value in all cases.

Examples:
- ¬(p ∧ q) ≡ ¬p ∨ ¬q
- ¬(p ∨ q) ≡ ¬p ∧ ¬q

These are De Morgan's laws.

## 4. Quantifiers

### Universal quantifier
∀x P(x) means "for all x, P(x) is true."

### Existential quantifier
∃x P(x) means "there exists an x such that P(x) is true."

Examples:
- ∀x (x + 1 > x) is true over the integers.
- ∃x (x^2 = 9) is true for x = 3 or -3.

## 5. Predicate Logic

Predicate logic extends propositional logic by allowing variables and properties.

For example:
P(x): "x is even"
Then P(4) is true, P(5) is false.

## 6. Proof Techniques

### Direct proof
To prove P → Q, assume P and show Q.

Example:
If n is even, then n^2 is even.
Assume n = 2k. Then n^2 = 4k^2 = 2(2k^2), so n^2 is even.

### Proof by contrapositive
To prove P → Q, prove ¬Q → ¬P.

This is often easier when the direct proof is difficult.

### Proof by contradiction
Assume the statement is false and derive a contradiction.

This is useful for proving irrationality, such as √2 being irrational.

### Proof by induction
Used to prove statements about integers, especially formulas and sequences.

The structure:
1. Base case: prove it for the first value.
2. Inductive hypothesis: assume it holds for n.
3. Inductive step: prove it holds for n+1.

## 7. Mathematical Induction

A classic example:
Prove 1 + 2 + ... + n = n(n+1)/2

Base case n = 1:
1 = 1(2)/2 = 1

Inductive assumption:
1 + ... + k = k(k+1)/2

Then:
1 + ... + k + (k+1) = k(k+1)/2 + (k+1)
= (k+1)(k+2)/2

Thus it holds for k+1.

## 8. Strong Induction

Sometimes you need more than the previous step. In strong induction, assume the statement is true for all values up to n and prove it for n+1.

This is useful in number theory and recursion.

## 9. Why Logic and Proof Matter

Logic is the foundation of rigorous reasoning. In discrete mathematics, proofs are not just about getting the right answer—they are about explaining why the answer is correct.

This matters in:
- algorithm correctness
- software verification
- database theory
- formal methods
- cryptography

## 10. Summary

The main ideas in logic are propositions, connectives, quantifiers, and proof strategies. Once you understand how to reason clearly, you can evaluate claims, build proofs, and analyze algorithms with precision.
