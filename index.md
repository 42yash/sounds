---
layout: default
title: Sounds 
---

# Sounds

{% for page in site.pages %}
  {% if page.path contains 'markdown/' %}
    {% assign title = page.title | default: page.name | remove: '.md' | replace: '-', ' ' | capitalize %}
    * [{{ title }}]({{ page.path | remove: '.md' | prepend: '/' | append: '.html' | relative_url }})
  {% endif %}
{% endfor %}
