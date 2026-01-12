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
  * Topic: Numerical algorithms for tensor decompositions and applications
  * Advisor: Prof. Lieven De Lathauwer  
  

* M.Sc. in Data Science, Skoltech, Moscow, Russia, 2020 – 2022
  * Thesis: Spatiotemporal forecasting with application to the weather forecast
  * Advisor: Prof. Ivan Oseledets, Dr. Rukhsan Ul Haq
  * GPA: 4.7/5   
  

* B.Tech in Electrical Engineering, IUST, India, 2015 – 2019
  * Thesis: Energy-Based Modeling of DC-DC Power Converters
  * Advisor: Dr. Shahkar Ahmad Nahvi
  * GPA: 9.18/10  
  


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

Software
======
  <ul>{% for post in site.software reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
