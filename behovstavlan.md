---
layout: default
title: Behovstavlan - Kastrullen
---

<div class="card-columns">
  {% for post in site.posts %}
    <div class="card">
      {% if post.image %}
        <img class="card-img-top" src="{{ post.image }}" alt="post.title">
      {% endif %}
      <div class="card-body">
        <h5 class="card-title">
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </h5>
        <p class="card-text">{{ post.excerpt }}</p>
        <p class="card-text"><small class="text-muted">{{ post.date | date: "%Y-%m-%d" }}</small></p>
      </div>
    </div>
  {% endfor %}
</div>
