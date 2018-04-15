---
title: releases
permalink: /releases/
layout: page
tag: releases
---


{% for post in site.tags['releases'] %}
  <h2>{% strip %}<a class="post-link" href="{{ post.url }}">{{ post.title }}</a>, {{ post.artist: | append: " " | append: post.format }}{% endstrip %}</h2>
{% endfor %}
