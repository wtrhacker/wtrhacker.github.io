---
title: What mad pursuit
description: Notes from a chromatin scientist at MIT.
permalink: /
---

<div class="intro">
  <p>Hello, I am a chromatin scientist at MIT.</p>
  <p>I use simulation, theory, and bioinformatics to study how chromatin folds across scales, and how genome organization relates to gene regulation and cellular identity.</p>
  <p class="intro-contact"><a href="mailto:trwang@mit.edu">Get in touch</a></p>
</div>

<section class="archive" aria-labelledby="writing-heading">
  <h2 class="section-label" id="writing-heading">Latest writing</h2>
  {% for post in site.posts %}
    <article class="post-preview{% if post.image %} has-image{% endif %}">
      <div class="post-preview-copy">
        {% assign words = post.content | number_of_words %}
        {% assign minutes = words | divided_by: 220 | plus: 1 %}
        <p class="post-preview-meta">
          <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %-d, %Y" }}</time>
          <span aria-hidden="true"> / </span>
          <span>{{ minutes }} min read</span>
        </p>
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        {% if post.subtitle %}<p class="post-preview-subtitle">{{ post.subtitle }}</p>{% endif %}
        <p class="post-preview-excerpt">{{ post.description }}</p>
        <p><a class="read-more" href="{{ post.url | relative_url }}">Read essay <span aria-hidden="true">&rarr;</span></a></p>
      </div>
      {% if post.image %}
        <a class="post-preview-image" href="{{ post.url | relative_url }}" tabindex="-1" aria-hidden="true">
          <img src="{{ post.image | relative_url }}" alt="">
        </a>
      {% endif %}
    </article>
  {% endfor %}
</section>
