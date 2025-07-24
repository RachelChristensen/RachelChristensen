---
layout: page
title: "Portfolio"
permalink: /portfolio/
---

# Portfolio

A collection of projects and work I’ve created or contributed to.

{% for item in site.portfolio %}
- [{{ item.title }}]({{ item.url }})
  - {{ item.description }}
{% endfor %}
