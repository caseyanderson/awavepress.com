---
title: press
permalink: /press/
layout: page
tag: press
---


{% for post in site.tags['press''] %}
<!-- <h2>{% strip %} {{ post.date | date: "%b %d %Y" }}, {{ post.title | append: " " | append: post.excerpt }}{% endstrip %}</h2> -->
<h2>{% strip %} {{ post.pub_date | date: "%b %d %Y" }}, {{ post.title | append: ", " | append: post.author | append: ", " | append: post.publisher | append: " " }} <a href= "{{post.pub_url}}">→</a> {% endstrip %}</h2>
{% endfor %}
