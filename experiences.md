---
layout: default
title: My Work Experiences
permalink: /experiences/
---

# My Work Experiences

Welcome to the My Experiences section! Here, you'll find posts about my work experiences at different companies, including the technologies I've used, the work styles, and the company cultures I've encountered.

## Posts
{% for post in site.posts %}
  {% if post.categories contains "experiences" %}
  <article>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </article>
  {% endif %}
{% endfor %}
