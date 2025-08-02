---
title: Journal
layout: default
permalink: /journal/
---

# Journal Entries

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%B %-d, %Y" }}</small>
  </li>
{% endfor %}
</ul>

