---
layout: page
theme: jekyll-theme-architect
title: Nicko's Blog
permalink: /blog/
---
{% for post in site.posts %}

      <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <h4>{{post.date}} -</h4>
      {{ post.excerpt | markdownify }}
    </li>
{% endfor %}
