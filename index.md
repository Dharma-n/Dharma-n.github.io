---
layout: page
title: Dharma-n.io
tagline: We create some new shit.
---
{% include JB/setup %}

## Blogs

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>