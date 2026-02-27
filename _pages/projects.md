---
layout: page
title: Research
permalink: /projects/
description: Integrated research on online safety, digital resilience, and cultural analytics through information, attention, behavior, and long-term discourse dynamics.
nav: true
nav_order: 3
horizontal: false
---

My research sits at the intersection of computational social science, cybersecurity, and natural language processing. I advance **online safety**, **digital resilience**, and **cultural analytics** through three connected lines of inquiry:

- Information and Knowledge Dynamics in Hidden Networks
- Attention and Behavior Dynamics on Public Platforms
- Meaning and Cultural Dynamics in Long-Term Discourse

The three subpages below reflect this integrated agenda. Across these streams, I combine methodological depth (NLP, survival modeling, panel methods, causal inference strategies) with applied relevance in online safety, platform governance, and public-interest computing.

The agenda is structured for externally funded, team-based research, with modular streams that support cumulative progress in data engineering, modeling, evaluation, and societal interpretation.

<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
