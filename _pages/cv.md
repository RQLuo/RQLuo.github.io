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
=========
* **New York University**  
  *Master of Applied Mathematics*, Sep 2023 - Jun 2025  
  GPA: 3.61/4.00  
  * Joined the **NYU VideoLab** from Electrical Engineering in Sep 2024 under the advisory of Professor Yao Wang and postdoctoral researcher Nikola Janjušević.
  * Researching the construction of interpretable deep-learning models for solving noisy 3D MRI reconstruction problems, forming the basis of my master's thesis.

* **University of Washington**  
  *Bachelor of Physics*, Sep 2019 - Jun 2023  
  GPA: 3.73/4.00

Work & Project Experience
=========================

* **Optimization of Unambiguous Recognition**  
  *May 2024 - Present*  
  * New York University
  * Duties include:
    * Optimized scheduling between disk, memory, and GPU by using asynchronous data processing and mounting, increasing GPU utilization from 60% to 95%.
    * Modified SwinGPT2 encoder structure to improve encoder inference efficiency by approximately 4 times without significant loss of accuracy.
    * Implemented sliding encoder-decoder streaming input and output, making input size of images or audio and output text unrestricted.

* **Unambiguous Recognition**  
  *Apr 2024 - May 2024*  
  * New York University
  * Duties include:
    * Proposed that unambiguous recognition should not solely use natural language corpus as the training set, and developed a multimodal model using SwinGPT2 structure for end-to-end visual encoding and text decoding.
    * [**Paper** https://arxiv.org/abs/2406.17148](https://arxiv.org/abs/2406.17148) and [**Code** https://github.com/RQLuo/MixTeX](https://github.com/RQLuo/MixTeX)
    * Mined and processed a dataset of 120M tokens of \LaTeX{} text labels and image inputs.
    * Trained MixTex for recognizing multilingual text mixed with formulas and tables.

* **Document Dewarping Algorithm**  
  *Apr 2022 - Jun 2022*  
  * University of Washington  
  * Duties include:
    * Proposed a contour-based mesh subdivision surface flattening method and applied it to scan curved surface pages. A non-neural network approach using traditional graphics methods, suitable for low-resource high-speed processing.
    * Six months after open-sourcing, CamScanner launched a similar feature.
    * [**Paper** https://arxiv.org/abs/2212.13489](https://arxiv.org/abs/2212.13489) and [**Code** https://github.com/RQ-Luo/contour-dewarp](https://github.com/RQ-Luo/contour-dewarp)

* **Multi-Speaker Voice Synthesis**  
  *June 2023 - August 2023*  
  * University of Washington  
  * Duties include:
    * Developed a neural network-based multi-speaker text-to-speech system for generating audiobooks.
    * Achieved 91% accuracy in identifying the gender, age, and emotion of novel dialogue characters using BERT.
    * Mined a 10GB speech dataset, assisted by Whisper for labeling.
    * Set up multi-GPU data parallel training on rented servers and completed model training within a week.
    * [**AI Novel Animation Demonstration Video**](https://www.bilibili.com/video/BV1QM4y1H72z)

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
* Currently signed in to 43 different slack teams
