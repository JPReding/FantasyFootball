---
layout: default
title: News
description: The week by week breakdown.
---
<h2 align="center">Breaking News</h2>
<ul>
  {% for post in site.posts %}
      <hr>
      <h2><a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>