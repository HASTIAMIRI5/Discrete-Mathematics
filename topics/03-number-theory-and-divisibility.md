# Topic 3: Number Theory and Divisibility

## 1. Divisibility

An integer a divides an integer b if there exists an integer k such that b = ak.

We write a | b.

Example:
3 | 12 because 12 = 3 × 4.

But 3 ∤ 10 because there is no integer k with 10 = 3k.

## 2. Prime Numbers

A prime number is an integer greater than 1 that has exactly two positive divisors: 1 and itself.

Examples:
2, 3, 5, 7, 11, 13, ...

A number greater than 1 that is not prime is composite.

## 3. Fundamental Theorem of Arithmetic

Every integer greater than 1 can be written uniquely as a product of prime numbers (ignoring order).

Example:
60 = 2^2 × 3 × 5

This theorem is central to number theory and cryptography.

## 4. Greatest Common Divisor (GCD)

The gcd of two integers a and b is the largest positive integer that divides both.

Example:
gcd(12, 18) = 6

### Euclidean Algorithm
The Euclidean algorithm efficiently computes gcd.

Example:
Compute gcd(48, 18):
48 = 18 × 2 + 12
18 = 12 × 1 + 6
12 = 6 × 2 + 0
So gcd(48,18)=6

## 5. Least Common Multiple (LCM)

The lcm of a and b is the smallest positive integer divisible by both.

Example:
lcm(12,18)=36

There is a useful identity:

lcm(a,b) × gcd(a,b) = a × b

## 6. Modular Arithmetic

We say a ≡ b (mod n) if n divides a - b.

Example:
17 ≡ 2 (mod 5) because 17 - 2 = 15 and 5 divides 15.

Modular arithmetic is used in:
- clocks
- hashing
- encryption
- computer arithmetic

## 7. Congruence Rules

If a ≡ b (mod n) and c ≡ d (mod n), then:
- a + c ≡ b + d (mod n)
- a - c ≡ b - d (mod n)
- ac ≡ bd (mod n)

These rules allow arithmetic to be done efficiently modulo n.

## 8. Fermat's Little Theorem

If p is prime and a is not divisible by p, then:

a^(p-1) ≡ 1 (mod p)

This theorem is fundamental in public-key cryptography.

## 9. Euler's Totient Function

φ(n) counts how many integers from 1 to n are relatively prime to n.

Example:
φ(12) = 4
because the numbers 1,5,7,11 are relatively prime to 12.

This function is important in RSA encryption.

## 10. Why This Topic Matters

Number theory studies the structure of integers. It has deep applications in:
- cryptography
- coding theory
- computer security
- algorithms
- digital systems

Even though it starts with basic division and remainders, it becomes extremely powerful when combined with modular arithmetic.

## 11. Summary

Number theory focuses on divisibility, primes, gcd, lcm, and modular arithmetic. These are not isolated ideas; together they form the arithmetic backbone of modern computing and security.
