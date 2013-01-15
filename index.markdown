---
title: Ron Paul's Texas Straight Talk
layout: default
---

<div id="container" class="isotope">
  {% for post in site.posts %}
  <article class="item month-{{ post.date | date: "%-m"}}">
    <p class="date-day">{{ post.date | date: "%d" }}</p>
    <p class="date-month">{{ post.date | date: "%b" }}</p>
    <h1 class="title">{{ post.title }}</h1>
  </article>
  {% endfor %}
</div>
