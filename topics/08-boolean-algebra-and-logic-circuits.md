# Topic 8: Boolean Algebra and Logic Circuits

## 1. Boolean Algebra

Boolean algebra is the algebra of true and false values, usually represented as 1 and 0.

The basic operations are:
- AND (∧)
- OR (∨)
- NOT (¬)

## 2. Boolean Laws

### Commutative laws
- a ∧ b = b ∧ a
- a ∨ b = b ∨ a

### Associative laws
- (a ∧ b) ∧ c = a ∧ (b ∧ c)
- (a ∨ b) ∨ c = a ∨ (b ∨ c)

### Distributive laws
- a ∧ (b ∨ c) = (a ∧ b) ∨ (a ∧ c)
- a ∨ (b ∧ c) = (a ∨ b) ∧ (a ∨ c)

### Identity and complement laws
- a ∧ 1 = a
- a ∨ 0 = a
- a ∧ ¬a = 0
- a ∨ ¬a = 1

## 3. Boolean Expressions

A Boolean expression combines variables with logic operators.

Example:
F = x ∧ (y ∨ ¬z)

Boolean expressions model digital logic conditions.

## 4. Logic Gates

Digital circuits are built with logic gates:
- AND gate
- OR gate
- NOT gate
- NAND, NOR, XOR, XNOR

Example:
An AND gate outputs 1 only when all inputs are 1.

## 5. De Morgan's Laws in Circuits

De Morgan's laws are especially important in circuit design:

¬(A ∧ B) = ¬A ∨ ¬B
¬(A ∨ B) = ¬A ∧ ¬B

These allow us to build equivalent circuits with different gate arrangements.

## 6. Canonical Forms

A Boolean function can be represented in:
- sum-of-products form
- product-of-sums form

These forms are useful for simplification.

## 7. Simplification

Boolean expressions can often be simplified using identities.

Example:
x ∧ (x ∨ y) = x
by absorption law

This reduces unnecessary components in hardware.

## 8. Applications

Boolean algebra is used in:
- digital computers
- circuit design
- memory systems
- program logic
- database queries

## 9. Summary

Boolean algebra gives a mathematical structure to logical statements and digital circuits. It is one of the main bridges between mathematical reasoning and computing hardware.
