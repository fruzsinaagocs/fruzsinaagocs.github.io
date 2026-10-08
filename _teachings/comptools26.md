---
layout: course
title: CSCI 5526 Computational Tools for Multiscale Problems
description: Physical phenomena are often described in terms of ordinary and partial differential equations (ODEs and PDEs) with interactions and features on multiple scales. Some of these systems are notoriously hard to solve but are of great interest in scientific and engineering applications. In this course you will learn about state-of-the-art methods and software for the fast numerical solution of such systems, focusing on several types of oscillatory ODEs and PDEs in complex geometric settings. We will cover hybrid methods for oscillatory and stiff ODEs, asymptotic approximations, specialized quadrature methods for numerical integration, and introduce powerful boundary integral-based methods for PDEs. We will review famous publications and use both long-standing and cutting edge software packages.
instructor: Fruzsina Agocs
year: 2026
term: Fall
course_id: comptools26
---

## Course Overview

Learning goals:

- Be familiar with established and novel numerical tools (methods and software) for fundamental computational tasks: interpolation, quadrature, solution of ODEs, solution of linear PDEs with boundary integral equation methods.
- Understand how to assess whether a numerical solution is satisfactory, learn to evaluate what accuracy one can reasonably demand.
- Learn to build robust numerical software and (unit, convergence) test it.
- Distill information from numerical analysis research; summarize, communitate results by presentation.
- Deliver constructive feedback on presentations.

Course plan:

- Fundamentals of computation
    - Floating point representation, condition number, backwards stability
- Components of differential equations
    - Interpolation, numerical differentiation, (smooth) quadrature
    - Complex contour deformation for oscillatory quadrature
- ODEs
    - Runge–Kutta methods, Butcher tableaus, stability and stiffness
    - Spectral methods
    - Asymptotic acceleration for linear oscillatory systems
    - Numerical Poincaré–Lindstedt for nonlinear oscillatory systems
- Integral equations I
    - What are integral equations? Nyström method, SVD, compact operators
- Integral equations II
    - Laplace’s equation, fundamental solution, properties of harmonic functions, Green’s representation theorem, boundary parameterization
- Integral equations III
    - Layer potentials, jump relations, interior/exterior Neumann/Dirichlet problems, complementary boundary value problem
- Integral equations IV
    - Helmholtz equation, scattering formulation, combined field integral equation, transmission formulation, low-rank interactions
- Fast algorithms
    - The fast multipole method, iterative methods and their convergence, singular / near-singular quadrature


## Prerequisites

- Linear algebra, calculus, complex analysis
- CSCI 3656 Numerical Computation
- Python or MATLAB programming language

## Resources

- Trefethen, L. N. (2019). Approximation theory and approximation practice. (available online through author)
- Driscoll, T. A., & Braun, R. J. (2017). Fundamentals of Numerical Computation. (available online through author)
- Corless, R. M., & Fillion, N. (2013). A graduate introduction to numerical methods. (PDF through publisher)
- Hairer, E., Nørsett, S. P., & Wanner, G. Solving Ordinary Differential Equations I-II. (PDF I and PDF II through publisher)
- Trefethen, L. N. (2000). Spectral methods in MATLAB. (Chapter-by-chapter PDFs through publisher)
- Alex Barnett’s Math 126 Numerical analysis for PDEs and wave scattering lecture notes (hand-written notes online)
- Kress, R. (1999). Linear integral equations. (PDF through publisher)
- Further resources will be listed in the lecture notes/homework sheets.

## Grading

- In class/take home hybrid assignments: 90%
- Attendance: 10%
