---
title: press
permalink: /press/
layout: page
tag: press
---


{% for post in site.tags['press''] %}
<h2>{% strip %}{{ post.date | date: "%b %d %Y" }}, {{ post.title | append: post.excerpt }}{% endstrip %}</h2>
{% endfor %}
