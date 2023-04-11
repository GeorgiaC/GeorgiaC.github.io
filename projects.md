---
permalink: /projects/
layout: default
title: Projects
---
# Projects

{% for image in site.static_files %}
{% if image.path contains 'images/' %}
  {{image.path}}
  ![Picture]({{site.baseurl}}{{image.path}})
{% endif %}
{% endfor %}
