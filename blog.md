---
layout: default
title: blog
permalink: /blog/
---

# blog

<ul>
  {% assign sorted_posts = site.static_files | where_exp:"file", "file.path contains 'posts/'" | sort: "name" | reverse %}
  {% for post in sorted_posts %}
    {% capture content %}
      {{ post.content | newline_to_br }}
    {% endcapture %}

    {% assign lines = content | split: '<br />' %}
    {% assign date = lines[0] | strip %}
    {% assign title_line = lines[1] | strip %}
    {% assign title = title_line | remove: '#' | strip %}

    <li>
      <a href="{{ post.path | relative_url }}">{{ title }}</a>
      <span style="color: var(--accent); font-size: 0.9rem;">({{ date }})</span>
    </li>
  {% endfor %}
</ul>
