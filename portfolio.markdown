---
title: Portfolio
date: 2018-06-11 22:40:00 Z
layout: default
category: myPage
---


<div class="grid">
{% for post in site.portfolio  %}
  <div class="grid-item">
    <img src="{{ portfolio.image }}"></img>
  </div>
{% endfor %}  
</div>
