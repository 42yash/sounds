---
layout: default
title: Sounds 
---

# Sounds

{% for page in site.pages %}
  {% if page.path contains 'markdown/' %}
    * [{{ page.title | default: page.name | remove: '.md' | capitalize | replace: '-', ' ' }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}
