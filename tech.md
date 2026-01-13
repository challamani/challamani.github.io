---
layout: default
title: Tech & Solutions
permalink: /tech/
---

# Technical Blogs

Welcome to the Tech & Solutions section! Here you'll find posts on solutions, challenges, and experiences — everything tech-related.

## Recent Posts

{% for post in site.posts %}
  {% if post.categories contains "tech" %}
  <article>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </article>
  
  ---
  {% endif %}
{% endfor %}
