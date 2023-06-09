# Quantum_Computing

This is the project, where we apply our knowledge and skills in quantum computing to explore Shor's algorithm.

The project involve a team of 7 members, with the aim of promoting and encouraging teamwork. The code is in master branch. 

# Shor's algorithm

Shor's algorithm, named after mathematician Peter Shor, is a quantum algorithm developed in 1994.
It is designed to solve the problem of integer factorization on a quantum computer. 
In simple terms, the algorithm aims to find the prime factors of a given integer, N.

## Overview

*Lemma*: Factoring is equivalent to finding a nontrivial squareroot of 1 mod N.

## Problem Statement

Traditional or classical algorithms for factorization require exponential time as the size of the number increases,
making them computationally expensive for large numbers. 

**Complexity:**
- Complexity on quantum computer: $\quad \mathcal{O}\;\Big((\log N)^2(\log \log N)(\log \log \log N)\Big)$

- Complexity on classical computer: $\quad \mathcal{O}\; \Big(e^{1.9(\log N)^{\frac{1}{3}}(\log \log N)^{\frac{2}{3}}} \Big)$


Shor's algorithm, on the other hand, takes advantage of the unique properties of quantum computers to provide a significant speedup for factorization.

By leveraging principles of quantum superposition and quantum interference, Shor's algorithm can efficiently find the prime factors of an integer. It achieves this by utilizing two main components: a quantum Fourier transform and a period-finding subroutine.

The quantum Fourier transform helps to encode the information about the factors into the quantum state of the computer, while the period-finding subroutine is responsible for extracting this information by finding the period of a particular function.

By combining these elements, Shor's algorithm can identify the prime factors of an integer significantly faster than classical algorithms, making it a powerful tool for certain applications such as breaking cryptographic systems based on integer factorization.


In summary, Shor's algorithm is a quantum algorithm designed to efficiently factorize large integers by exploiting the unique properties of quantum computers, providing a significant speedup compared to classical factorization algorithms.
