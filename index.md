---
layout: default
title: Home
---

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%B %d, %Y" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
