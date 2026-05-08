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
* Hybrid data-driven, physics-based acceleration of cardiovascular flow simulation &mdash; Stanford University (NSF Graduate Research Fellow, Ph.D. candidate), Spring 2021&ndash;Present
  * Supervisors: Prof. Alison Marsden, Prof. Eric Darve
  * Use ML to predict resistance and inductance for electric circuit surrogates that replace costly 3D finite-element cardiovascular simulations (minutes on a laptop vs. many hours on HPC).
  * Train models in JAX, PyTorch, and TensorFlow linking patient-specific vascular geometry to circuit parameters that reproduce high-fidelity 3D behavior; circuit analogs with learned parameters outperform heuristic resistances/inductances by roughly 50% error reduction.
  * Apply fluid-mechanics-informed modeling to reduce data needs (model form, non-dimensionalization, geometry discretization, feature selection).
  * Automate pipelines for geometry planning, meshing, and svMultiPhysics simulation for synthetic training data.
  * Optimize preprocessing, model architecture, and training choices; implement optimization for circuits with nonlinear ML components.
  * Maintain the [Vascular Model Repository](https://www.vascularmodel.com/); collaborate on GitHub; mentor junior students; organize [SimVascular](https://simvascular.github.io/) tutorials.

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* NSF Graduate Research Fellowship Program fellow; mentorship of junior students in the Cardiovascular Biomechanics Computation Lab.
* Maintainer, [**Vascular Model Repository**](https://www.vascularmodel.com/) &mdash; database and web presence for sharing vascular models.
* Tutorial organization and community support for [**SimVascular**](https://simvascular.github.io/) open-source cardiovascular modeling software.
