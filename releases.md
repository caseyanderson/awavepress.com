---
title: releases
permalink: /releases/
layout: page
tag: releases
---

{% for post in site.tags['releases'] %}

{% strip %}<h2>[{{ post.cat_num }}] <a class="post-link" href="{{ post.url }}">{{post.title }}</a>, {{ post.artist | append: ", " | append: post.format }}</h2>{% endstrip %}

{% endfor %}
