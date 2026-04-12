---
title: "Symplectic Hamiltonian hybridizable discontinuous Galerkin methods for linearized shallow water equations"
collection: publications
category: manuscripts
permalink: /publication/hdg-shallow-water
date: 2025-01-01
venue: "Computer Methods in Applied Mechanics and Engineering"
paperurl: "https://doi.org/10.1016/j.cma.2025.118383"
citation: "Núñez, C., & Sánchez, M. A. (2025). Symplectic Hamiltonian hybridizable discontinuous Galerkin methods for linearized shallow water equations. Computer Methods in Applied Mechanics and Engineering."
---

This paper focuses on the numerical approximation of the linearized shallow water equations using hybridizable discontinuous Galerkin (HDG) methods, leveraging the Hamiltonian structure of the evolution system. First, we propose an equivalent formulation of the equations by introducing an auxiliary variable. Then, we discretize the space variables using HDG methods, resulting in a semi-discrete scheme that preserves a discrete version of the Hamiltonian structure. The use of an alternative formulation with the auxiliary variable is crucial for developing the HDG scheme that preserves this Hamiltonian structure. The resulting system is subsequently discretized in time using symplectic integrators, ensuring the energy conservation of the fully discrete scheme. We present numerical experiments that demonstrate optimal convergence rates for all variables and showcase the conservation of total energy, as well as the evolution of other physical quantities.
