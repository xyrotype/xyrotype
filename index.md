---
layout: default
title: "xyrotype"
---

# Enlisted Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}" class="post-link-wrapper">
        <span class="post-title">{{ post.title }}</span>
        <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      </a>
    </li>
  {% endfor %}
</ul>
