---
layout: default
title: Behovstavlan - Kastrullen
---

<div class="card-columns">
  {% for need in site.needs %}

    <div class="card">
      {% if need.image %}
        <img class="card-img-top" src="{{ need.image | relative_url }}" alt="{{ need.title }}">
      {% endif %}
      <div class="card-body">
        <h5 class="card-title">
          <a href="{{ need.url | relative_url }}">{{ need.title }}</a>
        </h5>
        <p class="card-text">{{ need.excerpt }}</p>
        <p class="card-text"><small class="text-muted">{{ need.date | date: "%Y-%m-%d" }}</small></p>
      </div>
    </div>

  {% endfor %}
</div>
