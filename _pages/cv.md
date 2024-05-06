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
B.A. in Literatures in English (minors in Computer Science & Comparative Literature), Cornell University, 2024

Work experience
======
* Communications Assistant
  * Cornell University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Top 3 Programming languages: Python, Java, C#
* Project Management
* Machine Learning Model Development
  * PyTorch
  * NumPy
  * JAX
* Technical Writing
* Foreign Languages: Mandarin Chinese (Advanced Working Proficiency), Danish (Beginner)

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
* Underrepresented Minorities in Computing, Cornell University, 2022 President
* Cornell Data Science, Cornell University, Fall 2023 Project Lead
