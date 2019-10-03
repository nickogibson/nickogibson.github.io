---
title: Nicko's Blog
description: Recent posts
permalink: /blog/
---
<ul>
{% for post in site.posts %}
      <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <h4>{{post.date}} -</h4>
      {{ post.excerpt }}
    </li>
{% endfor %}
</ul>
