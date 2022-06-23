---
layout: default
title: mookax
---

<!-- 遍历分页后的文章 -->
{% for post in site.posts %}
  <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  <p class="author">
    <span class="date">{{ post.date }}</span>
  </p>
{% endfor %}
