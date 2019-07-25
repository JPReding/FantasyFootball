---
layout: default
title: Family Fantasy Football
---
## 2019 Family Fantasy Football 

Hope everyone's offseason was productive and we've learned a lot since letting the <a href="http://fantasy.espn.com/football/team?leagueId=215530&seasonId=2019&teamId=12" target="_blank">"Auto Draft King"</a> beat us in fantasy football.

<h2>Here's the latest news</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>