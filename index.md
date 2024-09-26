---
layout: cards
title: "Card Index"
---

# Card Index

Here are the cards:

<ul>
{% for card in site.pages %}
  {% if card.path contains 'cards/' %}
    <li><a href="cards{{ card.url }}">{{ card.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
