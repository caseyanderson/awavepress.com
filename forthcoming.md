---
title: forthcoming
permalink: /forthcoming/
layout: page
tag: forthcoming
---

{% for post in site.tags['forthcoming'] %}

{% strip %}<h2>[{{ post.cat_num }}] {{ post.url }} {{post.title }}, {{ post.artist | append: ", " | append: post.format }}</h2>{% endstrip %}

{% endfor %}
