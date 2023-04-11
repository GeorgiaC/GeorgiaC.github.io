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
  [![{{ project.title }}](/assets/images/projects/{{ project.name}}.jpg # list "{{ project.sound }}")]({{ project.url }})
{% endfor %}



