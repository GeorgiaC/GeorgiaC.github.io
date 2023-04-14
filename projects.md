---
permalink: /projects/
layout: default
title: Projects
---
# Projects

{% for project in site.projects %}
  <h2>
    <a href="{{ project.url }}">
      {{ project.title }}
    </a>
  </h2>
  <a href= "{{ project.url }}">
    <img src="../assets/images/projects/{{ project.name }}.jpg" class="list" alt="{{ project.title }}" title=" {{ project.sound}}">
  </a> 
{% endfor %}



