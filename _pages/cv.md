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
* M.S. in Computer Science, NYU Tandon School of Engineering, May 2021
* B.F.A. in Studio Art, New York University, May 2017

Experience
======
* Research Assistant: NYU Tandon Data, Intelligence, and Computation for Engineering (DICE) Lab
  * Fall 2020 \- present
  * Supervisor: Professor Chinmay Hegde
  * Conducted comprehensive literature review on state-of-the-art deep learning methods for numerical analysis and solving partial differential equations, with applications in physical simulation and design problems.
  * Reviewed methods such as physics-constrained neural networks (PDE-constrained optimization), constrained generative models, neural reduced basis methods.

* Graduate Teaching Assistant: CS/ECE-GY Deep Learning
  * Fall 2020, Spring 2021
  * Supervisor: Professor Chinmay Hegde
  * Deep learning fundamentals: algorithmic aspects (optimization, automatic differentiation), CNNs, recurrent models, generative models, and deep reinforcement learning, with applications in computer vision, NLP, and robotics.
  * Prepared interactive Python notebook teaching materials to supplement lectures with hands-on programming examples using PyTorch and TensorFlow frameworks; conducted recitations demonstrating notebooks with students.
  
Skills
======
* Languages: Python (primary/current), C++ (secondary/past)
* Technologies \& Frameworks: PyTorch, TensorFlow, Matlab/Simulink, Linux, OpenGL
* Assorted Interests: Signal recovery problems, abstract algebra, random matrix theory, neural tangent kernel \& networks in the infinite-width limit, Koopman operator theory, sculpture, violin, yoga
     
Selected Works
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
