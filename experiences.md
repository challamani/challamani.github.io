---
layout: default
title: My Work Experiences
permalink: /experiences/
---

# My Work Experiences

Welcome to My Experiences! Here you'll find posts about my work across different companies—covering the technologies I've used, the ways of working, and the cultures I've encountered.
 
---

## Recent Posts
{% for post in site.posts %}
  {% if post.categories contains "experiences" %}
  <article>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </article>
  
  ---
  {% endif %}
{% endfor %}
