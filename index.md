---
layout: cards
title: "Card Index"
---

# Card Index

Here are the cards:

<ul>
{% for card in site.pages %}
    <li><a href="cards/{{ card.url }}">{{ card.title }}</a></li>
{% endfor %}
</ul>
