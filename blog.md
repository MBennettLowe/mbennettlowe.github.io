---
layout: default
title: Blog
permalink: /blog/
---

# Blog

{% raw %}
{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </article>
{% endfor %}
{% endraw %}