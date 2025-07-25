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
* Ph.D. in Engineering Science (Electrical Engineering), KU Leuven, Belgium, 2023 – Present  
  * Advisor: Prof. Lieven De Lathauwer  
  * Topic: Numerical algorithms for tensor decompositions and applications

* M.Sc. in Data Science, Skolkovo Institute of Science and Technology, Moscow, Russia, 2020 – 2022  
  * GPA: 4.7/5  
  * Advisor: Prof. Ivan Oseledets  
  * Thesis: Spatiotemporal forecasting with application to the weather forecast

* B.Tech in Electrical Engineering, Islamic University of Science and Technology, India, 2015 – 2019  
  * GPA: 9.18/10  
  * Thesis: Energy-Based Modeling of DC-DC Power Converters


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
