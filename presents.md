---
title: presents
permalink: /presents/
layout: page
tag: presents
---

{%- for post in site.tags['presents'] -%}

{% strip %}<h2>{{ post.calendar | append: ", " | append: post.event-type }}: <a href="{{ post.url }}">{{post.title}}</a>, {{ post.venue | append: ", " | append: post.location | append: ", " | append: post.time | append: ", " | append: post.cost }}</h2>{% endstrip %}

{%- endfor -%}

