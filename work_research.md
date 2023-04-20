---
permalink: /work_research/
layout: default
title: Work and Research
---
# Work and Research

<div class="row">
  {% for project in site.work_research %}
    <div class="column">
      <img src="../assets/images/work_research/{{ project.name }}.jpg" class="listimg" alt="{{ project.title }}" title="{{ project.action }}">
      <a href= "{{ project.url }}">
        <div class="overlay">
          <div class="text">{{ project.title }}</div>
        </div>
      </a>
    </div>
  {% endfor %}
</div>