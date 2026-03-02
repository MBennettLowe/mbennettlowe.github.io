---
layout: default
title: Blog
permalink: /blog/
---

# Blog

Total posts: {{ site.posts.size }}

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}