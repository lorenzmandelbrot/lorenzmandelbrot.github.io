---
layout: default
title: "Home"
---

# Welcome to Lorenz MandelBrot’s Blog

Hello! This is my technical blog about HFT Market Making, mathematics, and engineering.  
Check out recent posts below or head to the [Archive](archive.md) for all posts.

{% for post in site.posts limit: 5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

---