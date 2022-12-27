---
title: "PowerLLEL_Channel"
collection: software
excerpt: 'PowerLLEL_Channel is a Powerful paraLLEL solver for incompressible turbulent Channel flow. It is developed and optimized for massively-parallel Direct Numerical Simulation (DNS) of turbulent channel flow at high Reynolds number'
---

PowerLLEL_Channel is a **Power**ful para**LLEL** solver for incompressible turbulent **Channel** flow. It is developed and optimized for massively-parallel Direct Numerical Simulation (DNS) of turbulent channel flow at high Reynolds number, e.g., $Re_{\tau} \approx 10^4$. The Navier-Stokes (NS) equations are solved by an explicit second-order Runge-Kutta based projection method. The second-order central difference scheme is used for the spatial discretization. The Pressure Poisson Equation (PPE) is efficiently solved by the FFT-based direct method, combined with the Parallel Diagonal Dominant (PDD) algorithm for the tridiagonal system.

PowerLLEL_Channel is mainly written in Fortran 90/2003 with reasonable modularity so that it can be extended in a sustainable manner. For performance reason, a C version of the PPE solver is also provided. Using a 2D pencil-like domain decomposition and the MPI+OpenMP hybrid parallel programming model, PowerLLEL_Channel shows excellent parallel performance with up to $10^4$ CPU cores, on a number of HPC systems, e.g., Tianhe-2A and TACC Frontera.

**Download**

[Github](https://github.com/xiejb6/PowerLLEL_Channel)

**Reference**

Jiabin Xie, Jianchao He, Yun Bao & Xi Chen (2021) A Low-Communication-Overhead Parallel DNS Method for the 3D Incompressible Wall Turbulence, International Journal of Computational Fluid Dynamics, 35:6, 413-432, DOI: [10.1080/10618562.2021.1971202](https://doi.org/10.1080/10618562.2021.1971202) [[arXiv preprint](https://arxiv.org/abs/2104.08863v2)]