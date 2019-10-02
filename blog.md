---
layout: page
title: "Nicko's Blog"
permalink: "https://nickogibson.github.io/Blog"
---
{% for posts in site.posts %}
  <h2>{{ post.title }} - </h2>
  <h4>{{post.date}} -</h4>
  <p>{{ post.content | markdownify }}</p>
{% endfor %}
