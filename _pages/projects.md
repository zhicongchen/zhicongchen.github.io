---
layout: page
title: Research
permalink: /projects/
description: My research develops computational methods for online safety, social sensing, and multilingual large-scale text mining, with emphasis on privacy, security, and societal impact.
nav: true
nav_order: 3
horizontal: false
---

My research sits at the intersection of **computational social science**, **cybersecurity**, and **natural language processing**. I build reproducible computational pipelines for behavioral trace data, text corpora, and survey data to study online safety, platform dynamics, and sociotechnical risk.

The three subpages below reflect one integrated agenda: (1) **privacy and security in decentralized and anonymous systems**, (2) **social sensing and behavioral analytics for digital resilience**, and (3) **multilingual NLP and text mining for cultural and geopolitical analytics**. Across these streams, I combine methodological depth (NLP, survival modeling, panel methods, causal inference strategies) with applied relevance in online safety, platform governance, and public-interest computing.

The agenda is structured for externally funded, team-based research. Each stream is modular, allowing PhD students to lead identifiable subproblems (data engineering, modeling, evaluation, and societal interpretation) while contributing to a coherent long-term program.

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
