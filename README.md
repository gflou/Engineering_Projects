# Engineering_Projects

This repository contains four engineering projects completed as part of coursework at Aristotle University of Thessaloniki. Each project is documented in a PDF report describing the problem definition, assumptions, numerical methods, and results.

The projects focus on computational fluid dynamics, structural analysis, and dynamical system modeling. While only PDF reports are included, the work reflects the computational approaches and numerical implementations used in each study.


## Projects

### CFD Plate

This project focuses on laminar flow over a flat plate, modeled as a one-dimensional boundary layer problem. The objective is to study velocity development along the plate using numerical time integration methods.
Python was used to implement the solution, applying both the Forward Euler and Backward Euler methods to analyze the flow behavior and numerical performance.



### CFD Cavity

This project examines incompressible fluid flow inside a cavity using computational fluid dynamics. The problem is formulated as a two-dimensional flow case and serves as a classical benchmark for validating numerical solvers.
The simulation was implemented in Python, using the Alternating Direction Implicit (ADI) method to solve the governing equations efficiently and ensure numerical stability.



### Ground Vehicle

This project involves the dynamical modeling of a ground vehicle system, with emphasis on computing the system’s dynamic response under applied forces.
The numerical implementation was carried out in C++, using the Newmark method and the Central Difference method to perform time integration and evaluate vehicle dynamics.



### Truss

This project covers the dynamic structural analysis of a truss system. The goal is to calculate the structural response under time-dependent loading conditions.
C++ was used for the numerical implementation, employing the Backward Euler method, an implicit time integration technique, to ensure numerical stability in the structural response calculations.
