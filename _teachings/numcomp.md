---
layout: course
title: CSCI 3656 Numerical Computation
description: Physical phenomena are described in terms of ordinary and partial differential equations (ODEs and PDEs). Most of these systems cannot be solved on paper (i.e. do not possess an analytic solution), so we have to resort to numerical methods to find a solution. In this course you will learn about state-of-the-art methods and software for the fast and accurate numerical simulation of physical systems, starting from their fundamental components (linear solve, interpolation, differentiation, quadrature) and building up to ODE solvers.
instructor: Fruzsina Agocs
year: 2026
term: Spring
course_id: numcomp26
---

## Course Overview

Learning goals:

- Be familiar with established and novel numerical tools (methods and software) for fundamental computational tasks: interpolation, quadrature, solution of linear systems of equations, solution of ODEs.
- Understand how to assess whether a numerical solution is satisfactory, learn to evaluate what accuracy one can reasonably demand.
- Learn to build robust numerical code and (unit, convergence) test it.

Course plan:

- Fundamentals of computation
    - Floating point arithmetic
    - Conditioning, condition number
    - Backwards stability
    - Forward and backward error
    - The three most important graphs (convergence, complexity, work-precision)
- Interpolation
    - Equispaced nodes, the Runge phenomenon
    - Nodes vs bases: Vandermonde interpolation
    - Barycentric polynomial interpolation
    - Piecewise interpolation: linear, splines
- Differentiation
    - Low-order, high-order finite difference
    - Low-order and spectral differentiation matrices
    - Convergence and stability
- Quadrature (numerical integration)
    - Trapezoidal and composite trapezoidal rule, periodic trapezoidal
    - Gaussian quadrature
    - Convergence and stability
    - Adaptive integration
    - (Maybe: singular, near-singular quadrature)
- Numerical linear algebra
    - Review of important concepts: nullspace, rank, range, inverse, …
    - LU factorization, naive complexity, pivoting
    - Eigenvalues/eigenvectors, SVD
    - QR factorization, least squares
    - Iterative methods
- Rootfinding 
    - Newton's method
- (Maybe: ODEs)
    - Runge–Kutta methods, Butcher tableaus 
    - Adaptive stepsize
    - Stability and stiffness 
    - (Maybe: spectral methods, asymptotic acceleration)
- (Maybe: Fast algorithms)


## Prerequisites

- Basic computing / programming: ASEN 1320 or CSCI 1300 or CSCI 1320 or CSCI 2275 or ECEN 1310
- Calculus: APPM 1360 or MATH 2300
- Linear algebra: APPM 2360 or APPM 3310 or CSCI 2820 or MATH 2130 or MATH 2135
- Familiarity with Python (or some other programming language) encouraged

## Textbooks

- Trefethen, L. N. (2019). Approximation theory and approximation practice. (available onlineLinks to an external site. through author)
- Driscoll, T. A., & Braun, R. J. (2017). Fundamentals of Numerical Computation. (available onlineLinks to an external site. through author)
- Trefethen, L. N. & Bau, D. (2022). Numerical Linear Algebra. (PDFLinks to an external site. through publisher)
- Hairer, E., Nørsett, S. P., & Wanner, G. Solving Ordinary Differential Equations I-II. (PDF ILinks to an external site. and PDF IILinks to an external site. through publisher)
- Trefethen, L. N. (2000). Spectral methods in MATLAB. (Chapter-by-chapter PDFLinks to an external site.s through publisher)
- Further resources will be listed on Canvas.

## Grading

- Quizzes: 60%
    - 10 Quizzes total, equally weighted, drop the lowest two scores.
- Midterms: 30%
    - 2 Midterms, equally weighted.
- Attendance: 10%
    - 1/0 Score based on whether you’ve attended 80% of the classes. (34/42 classes)

