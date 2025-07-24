---
layout: page
title: "Blog"
permalink: /blog/
---

# Blog

Welcome to my blog! Here I share my coding journey, ideas, and more.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) <span style="color: #A79277;">({{ post.date | date: "%b %-d, %Y" }})</span>
{% endfor %}