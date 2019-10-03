---
title: NickoGibson Games IO
Description: Some games and stuff
permalink: /games/
---

{% for game in site.games %}
  <h2>
    <a href="{{ game.url }}">
      {{ game.title }} 
    </a>
  </h2>
  <b> Last update: {{game.date}}</b>
  <p>{{ game.excerpt  }}</p>
{% endfor %}
