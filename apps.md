---
title: App and Stuff
description: Some web apps and stuff
permalink: /apps/
---

{% for app in site.apps %}
  <h2>
    <a href="{{ app.url }}">
      {{ app.title }} 
    </a>
  </h2>
  <b> Last update: {{ app.date }} </b>
  <p>{{ app.excerpt  }} </p>
{% endfor %}
