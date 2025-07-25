<link rel="icon" type="image/x-icon" href="favicon.ico">


---
layout: home
title: "Welcome"
---

# Welcome to My Personal Blog & Portfolio

Hello! I’m Rachel Christensen. Here you’ll find my latest blog posts and a showcase of projects I’m proud of. I’m learning to code and sharing my journey and work along the way.

## Featured Portfolio

{% for item in site.portfolio limit:3 %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}

## Latest Blog Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) <span style="color: #A79277;">({{ post.date | date: "%b %-d, %Y" }})</span>
{% endfor %}


