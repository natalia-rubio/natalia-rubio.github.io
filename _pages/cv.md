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
* Mechanical Engineering (Ph.D. and M.S.), Stanford University, 2026
* Mechanical Engineering (B.S.), University of California Berkeley, 2020

Work experience
======
* Hybrid Data-driven Physics-Based Acceleration of Cardiovascular Flow Simulation &mdash; Stanford University (NSF Fellow, Ph.D. Candidate), Spring 2021&ndash;Present
  * Prof. Alison Marsden, Prof. Eric Darve
  * Used ML techniques to learn resistance and inductance values for 0D &ldquo;electric circuit&rdquo; models of patient-specific cardiovascular flows. These act as lightweight surrogates (&lt;1 min on personal laptop) for costly, high-fidelity 3D finite-element simulations (&gt;10 hours on 24+ cores of an HPC cluster).
  * Reduced error by over 50% compared to existing heuristics for complex, patient-specific anatomies including aortic, aortofemoral and pulmonary vasculature using learned circuit values.
  * Compiled functionality into a Python package for use in other lab members&rsquo; workflows.
  * Implemented and trained neural network models in JAX, PyTorch, and TensorFlow to learn the relationship between vascular geometry and circuit values.
  * Implemented automated pipelines (geometry planning, mesh generation, high-fidelity 3D fluid simulation with open-source svMultiPhysics solver on HPC clusters) to generate large, synthetic, high-fidelity training datasets for ML.
  * Leveraged physiological and fluid mechanics insights into model design to reduce training data demands in a data-scarce landscape, e.g. model form, physics-based non-dimensionalization scaling, discretization of vascular geometry, feature selection, data pre-processing.
  * Implemented novel optimization framework to solve electric circuit models complicated by nonlinear ML components.
  * Maintained the [Vascular Model Repository](https://www.vascularmodel.com/) database and website; collaborate on shared codebases via GitHub; mentor junior students; organize tutorials for the group&rsquo;s software ([SimVascular](https://simvascular.github.io/)).

* Implementation and comparison of graph neural network architectures &mdash; Pasteur Labs (Simulation Intelligence Intern), Summer 2024
  * Supervisor: Marta D&rsquo;Elia, Ph.D.
  * Implemented graph-based ML surrogates for unsteady fluid dynamics; ran Azure experiments comparing latent-space approaches for memory and compute.

* Variable-order fractional Laplacian for fractional Newtonian gravity &mdash; Stanford University (Ph.D. rotation), Winter 2021
  * Supervisor: Prof. Eric Darve
  * Implemented a variable-order Riesz-potential method for fractional Poisson problems in MATLAB and Julia.

* Corrosion of structural materials in liquid lead-bismuth eutectic (LBE) &mdash; UC Berkeley; Belgian Nuclear Research Centre (2017); Los Alamos National Laboratory (2018, 2019), Fall 2016&ndash;Summer 2020
  * Supervisor: Prof. Peter Hosemann
  * Experiments and electron microscopy for LBE-cooled systems; finite-element advection&ndash;diffusion corrosion model in Python for closed-loop flows.

Skills
======
Technical areas: Linear algebra, partial differential equations, numerical methods, convex optimization, machine learning, uncertainty quantification, fluid mechanics, feedback control, parallel computing

Programming Languages: Python, C++, MATLAB, Julia

ML frameworks: TensorFlow, PyTorch, JAX

Scientific computing: CUDA, MPI, OpenMP

Tools: Git, Linux, Slurm, Azure

Human languages: English (fluent), Spanish (proficient), French (proficient), German (proficient), Italian (proficient)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Service and leadership
======
* NSF Graduate Research Fellowship Program fellow; mentorship of junior students in the Cardiovascular Biomechanics Computation Lab.
* Maintainer, [**Vascular Model Repository**](https://www.vascularmodel.com/) &mdash; database and web presence for sharing vascular models.
* Tutorial organization and community support for [**SimVascular**](https://simvascular.github.io/) open-source cardiovascular modeling software.
