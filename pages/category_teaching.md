---
layout: page
title: "Teaching"
author: Till Grallert
date: 2015-07-04 21:36:17
categories:
- teaching
---

This page collects posts on courses I am teaching or have taught in the past.

<ul class="post-list">
{% for post in site.categories['teaching'] %}
  {% include post-list-item.html %}
{% endfor %}
</ul>