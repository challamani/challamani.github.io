---
layout: default
title: Lifestyle
permalink: /lifestyle/
---

# Lifestyle Blog

Welcome to the Lifestyle section! Here, you'll find posts sharing my experiences in areas like personal growth, travel, wellness, and more—everything outside of technology.

## Posts in Lifestyle

{% for post in site.posts %}
  {% if post.categories contains "tech" %}
  <article>
   <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
   <p>{{ post.excerpt }}</p>
  </article>
  {% endif %}
{% endfor %}
