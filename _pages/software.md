---
layout: archive
title: "Software"
permalink: /software/
---

{% for item in site.software %}
  <h2>
    <a href="{{ item.url }}">{{ item.title }}</a>
  </h2>
  <p>{{ item.excerpt }}</p>
{% endfor %}
