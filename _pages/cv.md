---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Mechanics, Sun Yat-sen University, 2022 (expected)
* B.E. in Theoretical and Applied Mechanics, Sun Yat-sen University, 2019

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Experience
======
* 2019.12 - present: Development of a parallel solver for large-scale turbulence direct numerical simulations
  * Supervisor: Prof. Yun Bao & Prof. [Xi Chen](https://www.researchgate.net/profile/Xi-Chen-134)
  * Responsible for the design of the solver framework and numerical algorithms, as well as parallel programming
  * Implement a low-communication-overhead parallel algorithm for tridiagonal systems, which accelerates the solving process of a large-scale Poisson's Equation by nearly 30%
  * Using a MPI/OpenMP hybrid parallel programming model, the solver shows excellent strong scalability to $10^4$ cores on two supercomputers, namely Tianhe-2A ([NSCC-GZ](http://nscc-gz.cn/)) and Frontera ([TACC](https://www.tacc.utexas.edu/))
  * Prepare for larger-scale simulations of turbulent flows

Internship
======
* 2021.04 - 2021.07: Research Intern in CAE R&D Center of [ZWSOFT CO., LTD.(Guangzhou)](https://www.zwsoft.com/)
  * Supervisor: Dr. [Dongyu Liu](https://www.researchgate.net/profile/Dongyu-Liu-10) & Mr. Yuanzhao Xu
  * Responsible for multi-core parallelization and optimization of the underlying math library of the structural solver on the x86 platform
  * Most of the optimized math functions/operations have a comparable performance to Intel MKL, accelerating the efficiency of core numerical algorithms like PCG
  * Several functions specific to finite element method are also highly optimized
  
Skills
======
* Programming Languages
  * Fortran, C/C++, Python, LaTeX, Matlab, Mathematica
* Parallel Computing
  * MPI, OpenMP, x86 intrinsic/inline assembly
* Other
  * Linux, Git
  * ParaView, Adobe Photoshop/Illustration
  
<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
