# Numerical Methods
    
This repository consists of various Numerical Methods developed as part of a numerical methods course that I took at Purdue Unviersity, through Astrodynamics research and out of my curiosity to investigate algorithms that can solve non-trivial mathematical problems. 

## Setup

The algorithms are implemented in Jupyter lab by leveraging numpy array. There are 5 files focused on each problem and various method for each problem are implemented. A discussion of the algorithms through examples is included to compare performance and assumptions.  

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
    * Composite Trapezoidal Polynomial

4. **Numerical Integration**
    * Midpoint mehtod
    * trapezoidal
    * simpson
    * 2pt gauss quadrature
    * 3pt gauss quadrature
    * forward euler
    * backward euler
    * Runge-Kutta 2<sup>nd</sup> order
    * Runge-Kutta 4<sup>th</sup> order

5. **Numerical Differentiation**
    * Forward Difference
    * Central Difference
    * Complex Step Differentiation

5. **Differential Algebraic Equation / Partial Differenital Equation solvers**
Solve Robin condition for equations of type:
    * 1D Heat Equation
    * Advect Eqation
    * Wave Equation
    * Laplace Equation

6. **Numerical Continuation**

## Reference
* "A Friendly Introduction to Numerical Analysis" by Brian Bradle, 2006.
* "The Complex-Step Derivative Approximation" by Martins, Strudza and Alonso
