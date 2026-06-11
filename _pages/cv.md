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
* Ph.D in Tropical Cyclone, City University of Hong Kong, 2029 (expected)
* M.S. in Physical Oceanography, Second Institute of Oceanography, MNR, 2025
* B.S. in Atmospheric Sciences, Nanjing University of Information Science & Technology, 2022
  
Skills
======
* Programming: Python, \\(\LaTeX\\), Matlab, Fortran
* Professional: Dynamic Meteorology, [tcpyPI](https://github.com/dgilford/tcpyPI), WRF/CM1 Simulation
* Languages: English, Mandarin, Cantonese

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% comment %}

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

{% endcomment %}
