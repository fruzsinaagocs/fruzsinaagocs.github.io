---
layout: course
title: CSCI 5636 Numerical Solution of Partial Differential Equations
description: Focuses on discretization techniques such as finite difference, finite element and finite volume methods, and parallel solution algorithms such as Krylov subspace methods, domain decomposition and multilevel methods.
instructor: Fruzsina Agocs
year: 2025
term: Spring
course_id: numpde
---

## Course Overview

Partial differential equations (PDE) describe the behavior of fluids, structures, heat transfer, wave propagation, and other physical phenomena of scientific and engineering interest. This course covers discretization of PDE using finite difference and collocation methods, finite volume methods, and finite element methods for elliptic, parabolic, and hyperbolic equations. For each method, we will discuss boundary conditions, generalization to high order, robustness, and geometric complexity. We will discuss foundational principles like will posedness, verification, and validation, as well as efficient methods for solution of the discretized equations and implementation in extensible software.

We will start with a brief refresher on numerical integration, approximation of functions, and numerical differentiation. We will extend this to finite difference methods for elliptic problems (like heat and pressure equilibrium) and time integration, producing methods that converge with arbitrarily high orders of accuracy. We will discover challenges when applying these methods to hyperbolic equations (which describe wave propagation and transport phenomena), especially nonlinear hyperbolic equations, and thus develop finite volume methods which rely on weaker assumptions. We will learn about shocks, rarefactions, and Riemann solvers. Finite volume methods are easy to use in complicated geometries and/or unstructured meshes, but achieving high order accuracy in such settings is unnatural and the methods can be awkward for elliptic and parabolic equations. Finite element methods offer a flexible and robust analysis framework as well as modular implementation that allows arbitrary order of accuracy even in complicated domains. We will introduce relevant concepts in continuum mechanics as we go.

In the second half of the semester, we will transition to more project-based learning. You will choose an open source software package with an active community and give a presentation to the class about the choice of methods, stakeholders and community functioning, and identify opportunities for contribution. You'll then form small teams of like interest and work on a contribution to be shared with the community. (Such contributions can take many different shapes, and need not involve code.)

Partial differential equations underly a broad range of high-fidelity models in science and engineering from atomic to cosmological scales. Upon completing this course, students possess an ability to:

- formulate problems in science and engineering in terms of partial differential equations
- understand the merits and limitations of the leading numerical methods used to solve PDE
- recognize and exploit structure to apply algorithms that improve performance and scalability
- select and use robust software libraries
- develop effective numerical software, taking into account stability, accuracy, and cost
- predict scaling challenges and computational costs when solving increasingly complex problems or attempting to meet real-time requirements
- interpret research papers and begin research in the field

## Prerequisites

Recommended:
- CSCI 2820 Linear Algebra (or equivalent)
- CSCI 3656 Numerical Computation (or equivalent)
- CSCI 4576 High-Performance Scientific Computing (or equivalent) 

## Resources

- LeVeque, Finite Difference Methods for Ordinary and Partial Differential Equations (CU students can download free from SIAM)
- LeVeque, Finite Volume Methods for Hyperbolic Problems and the Clawpack software.
- Toro, Riemann Solvers and Numerical Methods for Fluid Dynamics. (CU students can download free)
- Logg, Mardal, Wells, Automated Solution of Differential Equations by the Finite Element Method (The FEniCS Book). (free download)
- Trefethen, Spectral Methods in MATLAB. (CU students can download free from SIAM)
- Elman, Silvester, Wathen, Finite Elements and Fast Iterative Solvers with Applications in Incompressible Fluid Dynamics

## Grading

This course implements "Ungrading".

- Homeworks, to be submitted every 2 weeks: 30% total.
- Community project (second half of the semester): 60% total.
    - Community analysis proposal (7.5%): you'll write a one-page proposal (based on a template) where you identify the project you'll contribute to and find some information on it.
    - Community analysis presentation (7.5%): a 5-minute presentation on your contirbution ideas.
    - Contribution proposal (15%): a more detailed written proposal of your contribution that you'll attempt to communicate upstream.
    - Your contribution itself (22.5%).
    - Contribution presentation (7.5%): lightning presentations and breakout group discussions about your contributions.
- Portfolio: 10%. This is a journal to keep yourself organized, keep track of your goals, and collect ideas that relate to the class. It will take the form of a template repository, with detailed instructions and an example.

We will meet to reflect on your community project and portfolio. I will give constructive feedback and you will propose a grade.
