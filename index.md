---
layout: front
title: "Card Index"
---

# Card Index

Here are the cards:

<ul>
{% for card in site.pages %}
    <li>cards/<a href="{{ card.url }}">{{ card.title }}</a></li>
{% endfor %}
</ul>
