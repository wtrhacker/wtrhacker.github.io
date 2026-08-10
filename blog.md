---
title: Blog
description: Essays and notes by Tingran Wang on science, research, and life.
permalink: /blog/
---

<div class="intro">
  <p>Essays and notes on science, research, and life.</p>
  <br>
  <hr>
  <br>
  <h2>Essays</h2>
  <br>
  <ul class="post-list">
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span class="date">({{ post.date | date: "%B %Y" }})</span></li>
  {% endfor %}
  </ul>
</div>
