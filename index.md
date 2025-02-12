---
layout: default
title: Home
---

# Welcome to My Blog

Here you'll find my thoughts on photography and technology.

<div class="post-grid">
  {% for post in site.posts %}
    <a href="{{ post.url | relative_url }}" class="post-box">
      <h3>{{ post.title }}</h3>
      <div class="post-meta">{{ post.date | date: "%B %d, %Y" }}</div>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    </a>
  {% endfor %}
</div>