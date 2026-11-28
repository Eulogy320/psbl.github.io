---
title: Projects
nav:
  order: 3
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Our projects connect fundamental plant biology with predictive modeling, bioinformatics, and applications for sustainable agriculture. Each project combines data, experiments, and reusable tools to understand growth regulation and environmental resilience.

{% include tags.html tags="publication, resource, website, systems biology" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
