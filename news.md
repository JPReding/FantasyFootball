---
layout: default
title: News
description: The week by week breakdown.
---
<h1>Here's the scoop:</h1>
<ul>
  {% for post in site.posts %}
      <hr>
      <h2><a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>