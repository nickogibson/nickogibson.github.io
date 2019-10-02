---
layout: page
title: "Nicko's Blog"
permalink: /blog/
---
{% for posts in site.posts %}
  <h2>{{ post.title }} - </h2>
  <h4>{{post.date}} -</h4>
  <p>{{ post.content | markdownify }}</p>
{% endfor %}
