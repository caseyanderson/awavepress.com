---
title: releases
permalink: /releases/
layout: page
tag: releases
---

{%- for post in site.tags['presents'] -%}

{% strip %}<h2>{{ post.calendar }} <a href="{{ post.url }}">{{post.artist}}</a>, {{ post.location | append: ", " | append: post.venue | append: ", " | append: post.cost | append: ", " | append: post.time }}</h2>{% endstrip %}

{%- endfor -%}

