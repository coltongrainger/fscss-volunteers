---
title: Wiki 
author: Colton Grainger
order: 3
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>, <i>{{ post.date | date_to_string }}</i>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
