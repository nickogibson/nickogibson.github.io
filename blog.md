---
title: Nicko's Blog
Description: Recent posts
permalink: /blog/
---
{% for post in site.posts %}
      <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <h4>{{post.date}} -</h4>
      {{ post.excerpt }}
    </li>
{% endfor %}
