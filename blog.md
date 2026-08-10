---
title: Blog
description: Essays and notes by Tingran Wang on science, research, and life.
permalink: /blog/
---

# Blog

Essays and notes on science, research, and life.

<div class="post-list">
  {% for post in site.posts %}
    <article class="post-list-item">
      <p class="post-date">{{ post.date | date: "%B %-d, %Y" }}</p>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      {% if post.description %}<p>{{ post.description }}</p>{% endif %}
    </article>
  {% endfor %}
</div>
