---
permalink: /projects/
layout: default
title: Projects
---
# Projects

<div class="row">
  {% for project in site.projects %}
    <div class="column">
      <img src="../assets/images/projects/{{ project.name }}.jpg" class="listimg" alt="{{ project.title }}" title="{{ project.sound }}">
      <a href= "{{ project.url }}">
        <div class="overlay">
          <div class="text">{{ project.title }}</div>
        </div>
      </a>
    </div>
  {% endfor %}
</div>





