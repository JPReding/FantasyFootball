---
layout: default
title: News
description: The week by week breakdown.
---
<div class="dropdown">
  <button class="button">Dropdown</button>
  <div>
    {% for post in site.posts %}
        <a {{ post.date | date: "%m/%d" }} |  href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    {% endfor %}
  </div>
</div>
<ul>
  {% for post in site.posts %}
      <hr>
      <h2>{{ post.date | date: "%m/%d"}} | <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>