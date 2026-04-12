---
title: "HDG methods for the two-dimensional vector Laplacian"
collection: publications
category: manuscripts
permalink: /publication/vector-laplacian
date: 2026-04-01
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2604.05373"
citation: "Núñez Ramos, C., Cockburn, B., Sánchez, M. A. (2026). HDG methods for the two-dimensional vector Laplacian. arXiv:2604.05373"
---

We introduce new hybridizable discontinuous Galerkin (HDG) methods for solving the two-dimensional vector Laplacian equation under three types of boundary conditions: electric, magnetic, and Dirichlet. The method is formulated as a first-order system in which the rotational and divergence of the electric field are introduced as auxiliary variables.

We study the well-posedness of the method and prove that, when using piecewise polynomial approximations of degree \(k \ge 0\), the error in the \(L^2\) norm of the electric field converges at the optimal rate of \(k+1\). Additionally, we prove that the \(L^2\)-errors of the auxiliary variables, namely the rotational and divergence, converge with order \(k+1/2\).

We also show that the methods can be implemented in three different forms corresponding to three distinct hybridizations based on the choice of globally coupled unknowns among the numerical traces defined on the mesh skeleton. Finally, numerical experiments validate the theoretical convergence rates and demonstrate optimal convergence across all variables.
