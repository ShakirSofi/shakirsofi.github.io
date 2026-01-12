---
layout: archive
title: "Software"
permalink: /software/
---

{% raw %}
{% for item in site.software %}
  <h2>
    <a href="{{ item.url }}">{{ item.title }}</a>
  </h2>
  <p>{{ item.excerpt }}</p>
{% endfor %}
{% endraw %}
