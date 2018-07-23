---
title: forthcoming
permalink: /forthcoming/
layout: page
tag: forthcoming
---

{% for post in site.tags['forthcoming'] reversed %}

{% strip %}<h2>[{{ post.cat_num }}] {{post.title }}, {{ post.artist | append: ", " | append: post.format | append: post.arrival }}</h2>{% endstrip %}

{% endfor %}
