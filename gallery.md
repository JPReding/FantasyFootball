---
title: Hall of Fame
layout: default
description: Heroes get remembered, but legends never die
slider:
  text_color: white
  shadow_color: black
  slides: 
    - image: /assets/history/2009.png
      slide_html:
    - image: /assets/history/2010.png
      slide_html:
---
> Remember kid, there's heroes and there's legends. Heroes get remembered but legends never die...

The Sandlot

** The plan is to add an image gallery of past standings ** 

{% if page.slider %}
  {% include slider.html height="100" unit="%" transition="slide" duration="7" %}
{% endif %}

