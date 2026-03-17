---
layout: page
title: Portfolio
icon: fas fa-folder-open
order: 2
custom_css: portfolio
---

<div class="portfolio-grid">

  {% for project in site.projects %}
  <div class="project-card">
    <div class="project-header">
      <h3>{{ project.title }}</h3>
      <span class="project-status {{ project.status | downcase }}">{{ project.status }}</span>
    </div>
    <p class="project-desc">{{ project.description }}</p>
    <div class="project-tags">
      {% for tag in project.tags %}
      <span class="project-tag">{{ tag }}</span>
      {% endfor %}
    </div>
  </div>
  {% endfor %}

</div>
