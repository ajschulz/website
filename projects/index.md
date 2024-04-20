---
title: Research Projects
nav:
  order: 2
  tooltip: Current and past projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Research Projects

Below are current or recent projects that have resulted or will result in a first-author publication.

{% include tags.html tags="publication, research, teaching" %}

{% include search-info.html %}

## Featured

{% for project in site.data.projects %}
  {% if project.group == 'featured' %}
    {% include full-width-card.html data=project %}
  {% endif %}
{% endfor %}

## More

{% for project in site.data.projects %}
  {% if project.group != 'featured' %}
    {% include full-width-card.html data=project style="small" %}
  {% endif %}
{% endfor %}
