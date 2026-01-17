---
layout: default
title: My Experiences & Thoughts
---

# 👋 Welcome to My Blog

This is my personal space where I share experiences with various technologies, ideas, solutions, and the challenges I've faced both in tech and in life.

---

## 🔗 Quick Links

**[👤 About Me](https://manichalla.com/aboutme/)** - Get to know me better

---

## 📚 Explore Posts by Category

- **[💼 Experiences](https://manichalla.com/experiences/)** - Real-world stories and professional journey
- **[💻 Technical Blogs](https://manichalla.com/tech/)** - Deep dives into technology
- **[🌱 Lifestyle](https://manichalla.com/lifestyle/)** - Life beyond code

---

## 📝 Recent Posts

{% for post in site.posts %}
<article>
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
  <small>{{ post.date | date: "%B %d, %Y" }}</small>
</article>

---
{% endfor %}
