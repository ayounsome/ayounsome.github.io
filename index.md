---
layout: default
title: Raw Thots
---

# Raw Thots

A personal archive of thoughts, emotions, and musings written over a few years.

---

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
