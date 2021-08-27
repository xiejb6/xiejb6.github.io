---
title: "A low-communication-overhead parallel method for the 3D incompressible wall turbulence"
collection: publications
permalink: /publication/2021-08-15-IJCFD-A-low-communication-overhead-parallel-method-for-wall-turbulence
excerpt: 'This paper presents a low-communication-overhead parallel method for direct numerical simulations of the 3D incompressible wall turbulence. A fully explicit projection method with second-order space-time accuracy is adopted. Combined with fast Fourier transforms, the parallel diagonal dominant (PDD) algorithm for the tridiagonal system is employed to solve the pressure Poisson equation.'
date: 2021-08-15
venue: 'International Journal of Computational Fluid Dynamics'
paperurl: 'https://xiejb6.github.io/files/2021-08-15-IJCFD-A-low-communication-overhead-parallel-method-for-wall-turbulence.pdf'
citation: '<b>Xie, J.</b>, He, J., Bao, Y., & Chen, X. (2021). A low-communication-overhead parallel method for the 3D incompressible wall turbulence. <i>International Journal of Computational Fluid Dynamics</i>. https://doi.org/10.1080/10618562.2021.1971202.'
---

# Abstract

This paper presents a low-communication-overhead parallel method for direct numerical simulations of the 3D incompressible wall turbulence. A fully explicit projection method with second-order space-time accuracy is adopted. Combined with fast Fourier transforms, the parallel diagonal dominant (PDD) algorithm for the tridiagonal system is employed to solve the pressure Poisson equation, differing from its recent applications to compact scheme derivatives computation (Abide et al. 2017) and alternating-direction-implicit method (Moon et al. 2020). The number of all-to-all communications is decreased to only two, in a 2D pencil-like domain decomposition. The resulting MPI/OpenMP hybrid parallel code shows excellent strong scalability up to $10^4$ cores and small wall-clock time per timestep. Numerical simulations of turbulent channel flow at different friction Reynolds numbers ($Re_{\tau}$ = 550, 1000, 2000) have been conducted and the statistics are in good agreement with the reference data and the recent scaling theories (Chen et al. 2019; Chen \& Sreenivasan 2021). The proposed method allows massively simulation of wall turbulence at high Reynolds numbers as well as many other incompressible flows.