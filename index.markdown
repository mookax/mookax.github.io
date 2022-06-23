---
layout: default
title: mookax
---

{% for post in site.posts %}
  ---
  <h1><a href="{{ post.url }}">{{ post.title }}</a></h1>
  <p>{{ post.excerpt }}</p>
{% endfor %}


<br>

{% for album in site.go %}
  ---
  <h1><a href="{{ album.url }}">{{ album.title }}</a></h1>
  <p>{{ album.categories }}</p>
{% endfor %}

<br>

{% for album in site.cc %}
  ---
  <h1><a href="{{ album.url }}">{{ album.title }}</a></h1>
  <p>{{ album.categories }}</p>
{% endfor %}


<br>
<br>
