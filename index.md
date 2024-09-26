---
layout: default
title: "Card Index"
---

# Card Index

Here are the cards:

<ul>
{% for card in site.pages %}
  {% if card.path contains 'cards/' %}
    <li><a href="{{ card.url }}">{{ card.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
