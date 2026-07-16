---
layout: default
title: Blog
permalink: /blog/
---

# Blog

Here are my latest updates.

{% for post in site.posts %}

## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

{% endfor %}
