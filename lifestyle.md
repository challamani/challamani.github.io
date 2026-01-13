---
layout: default
title: Lifestyle
permalink: /lifestyle/
---

# Lifestyle Blog

Welcome to the Lifestyle section! Here, you'll find posts sharing my experiences in areas like personal growth, travel, wellness, and more—everything outside of technology.

## Recent Posts

{% for post in site.posts %}
  {% if post.categories contains "lifestyle" %}
  <article>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </article>
  
  ---
  {% endif %}
{% endfor %}
