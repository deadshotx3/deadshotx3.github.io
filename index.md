---
layout: default
title: Welcome to Deadshotx3's Blog
description: A blog about photography and technology
---

# Welcome to My Blog

Hello! I'm Deadshotx3, and this is my blog where I share insights about photography, technology, and web development.

## Latest Blog Posts

<div class="post-grid">
  {% for post in site.posts %}
    <a href="{{ post.url | relative_url }}" class="post-box">
      <h3>{{ post.title }}</h3>
      <div class="post-meta">{{ post.date | date: "%B %d, %Y" }}</div>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    </a>
  {% endfor %}
</div>

## About Me

I'm passionate about capturing moments through photography and exploring new technologies. This blog is where I share my experiences and knowledge with you.

Feel free to explore the posts and reach out if you have any questions!