---
title: wiki 
author: Colton Grainger
order: 4
---

### Orientation 
<ul>
{% for post in site.tags["orientation"] %}
      <dt>
	<a href="{{ post.url }}">{{ post.title }}</a> 
      </dt>
{% endfor %}
</ul>

### Statistics 
<ul>
{% for post in site.tags["statistics"] %}
      <dt>
	<a href="{{ post.url }}">{{ post.title }}</a> 
      </dt>
{% endfor %}
</ul>

### Activities 
<ul>
{% for post in site.tags["activities"] %}
      <dt>
	<a href="{{ post.url }}">{{ post.title }}</a> 
      </dt>
{% endfor %}
</ul>

## Chronological
<dl>
  {% for post in site.posts %}
      <dt>
	<a href="{{ post.url }}">{{ post.title }}</a>, <i>{{ post.date | date: "%Y-%m-%d" }}</i>
      </dt>
      <dd>
	{{ post.excerpt }}
      </dd>
  {% endfor %}
</dl>
