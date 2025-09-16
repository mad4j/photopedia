---
layout: default
---

<div class="photographer-grid">
{% for p in site.photographers %}
  <a href="{{ p.url | relative_url }}" class="photographer-card">
    <img src="{{ '/thumbs/' | append: p.thumb | relative_url }}" alt="{{ p.title }}">
    <div class="card-title">{{ p.title }}</div>
  </a>
{% endfor %}
</div>