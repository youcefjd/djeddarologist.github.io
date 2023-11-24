---
layout: default
title: Home
---

# Welcome to My Blog

## Latest Articles

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})**
  {{ post.excerpt }}
{% endfor %}
