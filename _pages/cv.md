--- 
layout: archive
title: "CV"
permalink: /cv/ 
author_profile: true 
redirect_from: 
 -/resume 
---

{% include base_path %}

You can download my CV here: [📑 Single Column CV](/files/singlecol.pdf){:target="_blank"} or [📑 Double Column CV](/files/doublecol.pdf){:target="_blank"}.

## Education

* **DPhil (PhD), Wind & Marine Energy Systems & Structures**
  University of Oxford, UK (2023–Present)

  * Research on floating wind turbine wake dynamics using the Actuator Line Method (ALM)
  * Development of OpenFOAM-based ALM code
  * Large Eddy Simulations on ARCHER2 and ARC HPC systems
  * Model validation against experimental datasets
  * Data analysis using Python and ParaView

* **EPSRC Centre for Doctoral Training**
  University of Strathclyde, UK (2023–2024)

  * Intensive training in offshore renewable energy systems

* **MMathPhys, Mathematics & Physics (First Class Honours, 82%)**
  University of Manchester, UK (2019–2023)

  * Focus on continuum mechanics, numerical methods, and scientific computing
  * **MMath Project:** Finite element solver for Helmholtz equation (C++)
  * **MPhys Project:** Machine learning analysis of rectal contouring and toxicity (resulted in publication)

---

## Experience

* **Conference Organiser** (2026–Present)
  Wind & Marine Systems & Structures CDT, Oxford

  * Organising the Future Wind & Marine Conference (2027)
  * Responsible for fundraising and event logistics

* **Lab Demonstrator** (2025–Present)
  University of Oxford

  * Supported student labs in materials testing and computational modelling
  * Assisted with experimental design and debugging
  * Conducted interview-based assessments

* **Research Intern** (2022)
  University of Manchester

  * Investigated nonlinear dynamics in retinal injection systems
  * Designed experiments and analysed viscous fingering instabilities

* **Work Experience – National Grid** (2019)
  Low Frequency Demand Disconnection Team

  * Modelled system response to generation failure
  * Contributed to optimisation of disconnection procedures

---

## Skills

* **Programming:** Python, C++, C, MATLAB, Linux
* **HPC & Parallel Computing:** CUDA, HIP, MPI, OpenMP
* **Build & Automation:** Bash, SLURM, Make, CMake
* **Data Analysis & Visualisation:** NumPy, ParaView, VTK
* **CFD & Numerical Methods:** OpenFOAM, Finite Element Analysis
* **Typesetting:** LaTeX, Beamer, Word
* **Version Control:** Git, GitHub

---

## Awards & Certificates

* NVIDIA — Fundamentals of Accelerated Computing with CUDA C++
* Zero Institute — Climate Tech Hackathon (1st Place)
* University of Oxford — CUDA Programming on NVIDIA GPUs

---

## Publications (Full List)

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

## Talks

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

