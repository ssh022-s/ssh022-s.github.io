---
layout: about
title: about
permalink: /
subtitle: 

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >


news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

Machine Learning Engineer

## Interests
* Software Development
* Game Development
* Game AI
* Reinforcement Learning
* Machine Learning
* Robotics

## Projects {#projects}
<div class="projects">
  <!-- You can manually list or summarize your projects here -->
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>