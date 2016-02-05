---
layout: page
title: A brave new Hello World!
tagline: Supporting tagline
theme:
  name: twitter
---
{% include JB/setup %}

## Neil's blog

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

