---
layout: default
title: "Portfolio"
permalink: /portfolio/
---

<div class="gallery">
  {% assign sorted_projects = site.projects | sort: 'order' %}
  {% for project in sorted_projects %}
    <div class="thumb-card">
      <a href="{{ project.url | relative_url }}">
        {% assign first_image = project.gallery_items | where: "type", "" | first %}
        {% if first_image %}
        <img src="{{ '/thumbs/' | append: project.folder_name | append: '/' | append: first_image.image | relative_url }}" alt="{{ project.title }}">
        {% endif %}
        <h3>{{ project.title }}</h3>
        {% if project.description %}
        <p class="project-caption">{{ project.description }}</p>
        {% endif %}
      </a>
    </div>
  {% endfor %}
</div>
