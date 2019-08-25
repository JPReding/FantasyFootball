---
layout: default
title: News
description: The week by week breakdown.
---
<div class="dropdown">
  <button class="dropbtn">Dropdown</button>
  <div class="dropdown-content">
    {% for post in site.posts %}
        <hr>
        <h2>{{ post.date | date: "%m/%d"}} | <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a></h2>
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