---
title: About
description: Tingran Wang is a physics PhD candidate at MIT studying the three-dimensional organization of the mammalian genome.
permalink: /
---

<div class="intro">
  <p class="eyebrow">MIT Physics · Mirny Lab</p>
  <h1>Tingran Wang</h1>
  <p class="lede">I am a physicist who combines simulation, theory, and bioinformatics to study the mammalian genome and epigenome.</p>
</div>

I focus on the three-dimensional folding of chromatin at small and large scales, and its relationship to gene regulation and cellular identity. I am a Physics PhD candidate at MIT in [Leonid Mirny's group](https://mirnylab.mit.edu/).

<figure class="research-visual">
  <img src="{{ '/assets/images/chromatin-folding.webp' | relative_url }}" width="1440" height="960" alt="Conceptual visualization of a chromatin fiber folding into loops and compact domains.">
</figure>

<section class="latest-writing" aria-labelledby="latest-heading">
  <p class="section-label" id="latest-heading">Latest writing</p>
  {% assign latest = site.posts.first %}
  {% if latest %}
    <article class="featured-post">
      <p class="post-date">{{ latest.date | date: "%B %-d, %Y" }}</p>
      <h2><a href="{{ latest.url | relative_url }}">{{ latest.title }}</a></h2>
      {% if latest.description %}<p>{{ latest.description }}</p>{% endif %}
      <a class="text-link" href="{{ latest.url | relative_url }}">Read the essay <span aria-hidden="true">→</span></a>
    </article>
  {% endif %}
</section>
