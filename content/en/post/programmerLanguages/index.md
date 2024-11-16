---
title: Scientific programming languages.
summary: A short story about scientific programming languages.
date: 2024-11-16
authors:
  - admin
tags:
  - Markdown
  - RUDN
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

# Scientific programming languages.

In computer programming, a scientific programming language can refer to two levels of the same concept.

In a broad sense, a scientific programming language is a programming language that is widely used in computational science and computational mathematics. In this sense, C/C++ and Python can be considered scientific programming languages.

In a broader sense, a scientific programming language is a language designed and optimised for the use of mathematical formulas and matrices.[1] Such languages are characterised not only by the presence of libraries that perform mathematical or scientific functions, but also by the syntax of the language itself.[2] For example, neither C++ nor Python have built-in matrix types or functions for matrix arithmetic (addition, multiplication, etc.); instead, these functions are available through standard libraries. Scientific programming languages more broadly include ALGOL, APL, Fortran, J, Julia, Maple, MATLAB, Octave and R.[3][4]

Scientific programming languages should not be confused with scientific language in general, which broadly refers to the higher standards of accuracy, correctness, and conciseness expected of professionals using the scientific method.

## Examples

## Linear algebra

Scientific programming languages provide facilities for working with linear algebra. For example, the following programme in Julia solves a system of linear equations:

A = rand(20, 20) # A - matrix 20x20
b = rand(20) # b is a vector of 20 elements
x = A\b # x - solution of the equation A*x = b

Working with large vectors and matrices is a key feature of these languages, as linear algebra lays the foundation for mathematical optimisation, which in turn enables important applications such as deep learning.

## Mathematical Optimisation

In a scientific programming language, we can compute function optima using syntax that is close to a mathematical language. For example, the following code in Julia finds the minimum of the polynomial $ P(x,y)=x^{2}-3xy+5y^{2}-7y+3 $

using Optim

P(x,y) = x^ 2 - 3x*y + 5y^ 2 - 7y + 3

z₀ = [ 0.0
       0.0 ] # starting point for the optimisation algorithm

optimise(z -> P(z...), z₀, Newton();
         autodiff = : forward)

This example uses Newton's method for minimisation. Modern scientific programming languages use automatic differentiation to compute the gradients and Hesse matrices of a function given as input; see differentiable programming. Here, automatic differentiation in the forward direction was chosen for this task. Older scientific programming languages, such as the venerable Fortran, required the programmer to pass, in addition to the function being optimised, a function that computes the gradient and a function that computes the Hesse matrix.

The more is known about the function being minimised, the more efficient algorithms can be used. For example, convex optimisation provides faster computations when the function is convex, quadratic programming provides faster computations when the function is quadratic in its variables, and linear programming provides faster computations when the function is linear.