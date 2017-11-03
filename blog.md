---
title: Blog
author: Colton Grainger
order: 3
---

# Recent Posts

By sharing our experience at shelter, we can create a more transparent environment for [effective altruism](http://careyryan.com/files/EA_Handbook.pdf). 

<hr>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>, <i>{{ post.date | date_to_string }}</i>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
