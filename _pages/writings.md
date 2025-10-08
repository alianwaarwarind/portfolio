---
title: "Writings & Insights"
layout: archive
permalink: /posts/
author_profile: true
---

Welcome to my space for ramblings and randomness..

{% assign posts = site.posts | where: "categories", "blog" %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
