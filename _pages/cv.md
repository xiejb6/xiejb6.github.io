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
  * Duties included: 
  * Supervisor: Prof. Yun Bao & Prof. [Xi Chen](https://www.researchgate.net/profile/Xi-Chen-134)

Internship
======
* 2021.04 - 2021.07: Research Intern in CAE R&D Center
  * [ZWSOFT CO., LTD.(Guangzhou)](https://www.zwsoft.com/)
  * Duties included:
  * Supervisor: Dr. Dongyu Liu & Mr. Yuanzhao Xu
  
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
