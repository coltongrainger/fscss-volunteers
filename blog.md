---
title: Blog
author: Colton Grainger
order: 3
---

# Recent Posts

<hr>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>, <i>{{ post.created | date_to_string }}</i>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
