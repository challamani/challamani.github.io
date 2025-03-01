---
layout: default
title: Tech & Solutions
permalink: /tech/
---

# Tech Blog

Welcome to the Tech & Solutions section! Here you'll find my posts on solutions, challenges and experience. everything tech-related.

## Posts in Tech & Solutions

{% for post in site.posts %}
  {% if post.categories contains "tech" %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  </article>
  {% endif %}
{% endfor %}
