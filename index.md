---
layout: default
title: SPIKE GPU
---

### SPIKE GPU
<h4> An Implementation of a Recursive Divide-and-Conquer Parallel Strategy for Solving Large Systems of Linear Equations</h4>

**Goal:** This project proposes to investigate, produce, and maintain a methodology and its software
implementation that leverage emerging heterogeneous hardware architectures to solve billion-unknowns
linear systems in a robust, scalable, and efficient fashion. The two classes of problems targeted under this
project are banded dense and sparse general linear systems. Preliminary results suggest that the adopted
methodology displays a good strong-scaling attribute and its early implementation, called SPIKE, is one
order of magnitude faster than competitive software solutions.

**Motivation:** The task of solving a linear system is one of the most ubiquitous ingredients in the
numerical solution of Applied Mathematics problems. It is relied upon for the implicit integration of
Ordinary Differential Equation (ODE) and Differential Algebraic Equation (DAE) problems, in the
numerical solution of Partial Differential Equation (PDE) problems, in interior point optimization
methods, in least squares approximations, in solving eigenvalue problems, and in data analysis. In fact,
the vast majority of nonlinear problems in Scientific Computing are solved iteratively by drawing on local
linearizations of nonlinear operators and the solution of linear systems. Recent advances in (a) hardware
architecture; i.e., the emergence of General Purpose Graphics Processing Unit (GP-GPU) cards, and (b)
scalable solution algorithms, provide an opportunity to develop a new class of parallel algorithms that can
robustly and efficiently solve very large linear systems of equations.
