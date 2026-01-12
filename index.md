---
layout: default
title: My Experiences & Thoughts
---

# Welcome to My Blog

This is my personal blog, where I share my experiences with various technologies I've worked with, along with my ideas, solutions, and some of the challenges I've faced in life beyond tech.

[About Me](https://manichalla.com/aboutme/)

## Categories

- [Experiences](https://manichalla.com/experiences/)
- [Tech & Solutions](https://manichalla.com/tech/)
- [Lifestyle](https://manichalla.com/lifestyle/)

## Recent Posts

{% for post in site.posts %}
  <article>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}
