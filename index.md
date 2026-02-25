---
layout: default
title: Home
---

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%B %d, %Y" }}</span> &raquo; <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

RSS feed link: https://rkeysiv.github.io/movie-tracker/feed.xml
[RSS Feed]({{ "/feed.xml" | relative_url }})

