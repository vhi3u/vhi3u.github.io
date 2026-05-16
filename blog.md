---
layout: default
title: blog
permalink: /blog/
---

# blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title | downcase }}</a>
      <span style="color: var(--accent); font-size: 1em;">[{{ post.date | date: "%Y.%m.%d" }}]</span>
    </li>
  {% endfor %}
</ul>
