---
layout: page
title: Games
permalink: /games/
---

<ul class="games-list">
  {% for game in site.data.games %}
    <li>
      <iframe src="{{ game.url }}" width="552" height="167" frameborder="0"></iframe>
    </li>
  {% endfor %}
</ul>
