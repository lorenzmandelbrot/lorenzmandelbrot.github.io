---
layout: default
title: "Archive"
---

# Archive

All posts, in reverse chronological order:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) <small>({{ post.date | date_to_string }})</small>
{% endfor %}