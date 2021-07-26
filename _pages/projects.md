---
layout: page
title: Software
permalink: /software/
description: Please contact me if there are any issues with these packages.
nav: true
display_categories: true
horizontal: true
rank: 3
---
<div class="projects">
  <!-- Display projects without categories -->
      {% assign sorted_projects = site.projects | sort: "importance" %}
      <!-- Generate cards for each project -->
      {% if page.horizontal %}
        <div class="container">
          <div class="row row-cols-2">
          {% for project in sorted_projects %}
            {% include projects_horizontal.html %}
          {% endfor %}
          </div>
        </div>
      {% else %}
        <div class="grid">
          {% for project in sorted_projects %}
            {% include projects.html %}
          {% endfor %}
        </div>
      {% endif %}
</div>
