---
layout: default
title: Hello World!
---
Hello World!

<ul>
  {% for post in site.posts %}
    <li>{{ post.date | date_to_string }} &raquo; <a href="./{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
