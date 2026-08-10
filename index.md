---
title: About
description: Tingran Wang is a physics PhD candidate at MIT studying the three-dimensional organization of the mammalian genome.
permalink: /
---

<div class="intro">
  <div class="intro-content">
    <div class="intro-text">
      <p>I am a Physics PhD candidate at MIT in Leonid Mirny's group. I combine simulation, theory, and bioinformatics to study the mammalian genome and epigenome.</p>
      <br>
      <p>I focus on the three-dimensional folding of chromatin at small and large scales, and its relationship to gene regulation and cellular identity.</p>
      <br>
      <p><a href="mailto:trwang@mit.edu">email</a> / <a href="https://mirnylab.mit.edu/">Mirny Lab</a> / <a href="https://github.com/wtrhacker">github</a></p>
      <br>
    </div>
    <div class="intro-image">
      <img src="{{ '/assets/images/tingran-wang.webp' | relative_url }}" width="600" height="563" alt="Tingran Wang" class="headshot">
    </div>
  </div>
</div>

<section class="links" aria-labelledby="writing-heading">
  <hr>
  <br>
  <h2 id="writing-heading">Writing</h2>
  <br>
  {% assign latest = site.posts.first %}
  {% if latest %}
    <ul>
      <li><a href="{{ latest.url | relative_url }}">{{ latest.title }}</a> <span class="date">({{ latest.date | date: "%B %Y" }})</span></li>
    </ul>
  {% endif %}
</section>
