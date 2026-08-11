---
title: Chromatin Notes
description: Notes from a chromatin scientist at MIT.
permalink: /
---

<div class="intro">
  <p>Hello, I am a chromatin scientist at MIT.</p>
  <br>
  <p>I use simulation, theory, and bioinformatics to study how chromatin folds across scales, and how genome organization relates to gene regulation and cellular identity.</p>
  <br>
  <p><a href="mailto:trwang@mit.edu">Contact</a></p>
</div>

<section class="links" aria-labelledby="writing-heading">
  <hr>
  <br>
  <h2 id="writing-heading">Writing</h2>
  <br>
  <ul class="post-list">
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <span class="date">({{ post.date | date: "%B %Y" }})</span></li>
  {% endfor %}
  </ul>
</section>
