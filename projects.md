---
layout: default
title: Projects
---

<div class="project-grid">
  {% for project in site.projects %}
    <div class="project-card">
      <h3>{{ project.title }}</h3>
      <p class="summary">{{ project.summary }}</p>
      <span class="tech">{{ project.tech }}</span>
      <a href="{{ project.url }}">Read more...</a>
    </div>
  {% endfor %}
</div>
