---
layout: default
title: Family Fantasy Football
---
<img class="center" src="/assets/fantasy_football.png" alt="Fantasy Football">
<h1 align="center" >2019 Family Fantasy Football</h1>
Hope everyone's offseason was productive and we've learned a lot since letting the <a href="http://fantasy.espn.com/football/team?leagueId=215530&seasonId=2019&teamId=12" target="_blank">"Auto Draft King"</a> beat us in fantasy football.

I thought it would be fun to have a central place to document all the story lines, prizes, and history our time chasing fantasy glory.
### Start Here
If the seasons hasn't started yet, make sure you <a href="http://sportsfamily.club/2019/08/21/welcome-back.html"><strong>start here</strong></a>

👇 In the future, you can quickly jump down here to stay current.

<h1>Latest Post</h1>
{% for post in site.posts limit:1 %}
<div> {{site.posts.first}} </div>
{% endfor %}

### Here's the latest news:
<ul>
  {% for post in site.posts limit:2 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>