# Numerical Methods
    
This repository consists of various Numerical Methods algorithms that I wrote as part of a graduate level numerical methods course that I took at Purdue Unviersity, through my Astrodynamics research and out of my curiosity to investigate algorithms that can solve non-trivial mathematical problems. 

## Setup

The algorithms are implemented in Jupyter lab by leveraging numpy array. There are 6 files focused on each problem and various method for each problem are implemented. A discussion of the algorithms through examples is included to compare performance and assumptions.  

## List of methods implemented

1. **Root-finding algorithms**
    * Bisection method
    * Newton's method (Newton-Raphson method)
    * Secant method
    * Fixed-point iteration method
    
2. **Linear Equation solvers**
    * Gaussian Elimination with No Pivoting(opt = 1) and Scaled Partial Pivoting (opt = 2)
    * Conjugate Gradient Method (Minimization Method)
    * Gauss-Sidel Method (Splitting Method)
    * Jacobi Method (Splitting Method)
    * SOR Method (Splitting Method)

3. **Numerical interpolation and Curve Fitting** 
    * Lagrange's form of the interpolation polynomial
    * Newton's form of the interpolation polynomial

4. **Numerical Integration**
    * Midpoint Rule
    * Trapezoidal Rule
    * Simpson's Rule
    * Forward Euler's Method
    * Backward Euler's Method
    * Runge-Kutta 4<sup>th</sup> order
    * Composite Trapezoidal Rule
    * 2-Point Gaussian Quadrature Rule
    * 3-Point Gaussian Quadrature Rule
   
5. **Numerical Differentiation**
    * Forward Differentiation
    * Central Differentiation
    * Complex Step Differentiation

5. **Differential Algebraic Equation / Partial Differenital Equation solvers**
    * 1D Heat Equation
    * Advect Eqation
    * Wave Equation
    * Laplace Equation (Contour Plot!)

6. **Numerical Continuation**
    * Natural Paramter Continuation
    * Pseudo-arc length continuation 
    
__Checkout my contribution to Poliastro to see the implementation of Numerical Continuation schemes__

## Reference
* "A Friendly Introduction to Numerical Analysis" by Brian Bradle, 2006.
* "The Complex-Step Derivative Approximation" by Martins, Strudza and Alonso
