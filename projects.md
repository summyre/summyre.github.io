---
layout: default
title: Projects
---

<div class="project-grid">
  {% for project in site.projects %}
    <div class="project-card">
      <h3>{{ project.title }}</h3>
      {% if project.summary %}
        <p class="summary">{{ project.summary }}</p>
      {% endif %}
      {% if project.tech %}
      <span class="tech">{{ project.tech }}</span>
      {% endif %}
      {% if project.github %}
      <p><a href="{{ project.github }}" target="_blank">Read more</a></p>
      {% endif %}
    </div>
  {% endfor %}
</div>
