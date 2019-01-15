---
title: press
permalink: /press/
layout: page
tag: press
---


{% for post in site.tags['press'] %}

<h2>{{ post.pub_date | date: "%b %d %Y" }}, {{ post.title | append: ", " | append: post.author | append: ", " | append: post.publisher | append: " " }} <a href= "{{post.pub_url}}" target="_blank">→</a></h2>

{% endfor %}
