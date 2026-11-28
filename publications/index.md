---
title: Publications
nav:
  order: 2
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-book-open" %}Publications

This archive is based primarily on Rodrigo Gutiérrez's CV (CV RG). Historical VirtualPlant records are used only to add unique publications that are missing from the CV, with duplicates removed.

{% assign publication_count = site.data.citations | size %}
<div class="publication-count" aria-label="{{ publication_count }} publications in Publications">
  <span class="publication-count-number">{{ publication_count }}</span>
  <span class="publication-count-label">publications</span>
</div>

<h2 class="publication-count-heading">{{ publication_count }} publications in our archive</h2>

{% include section.html %}

## Highlighted

{% include citation.html lookup="doi:10.1002/ece3.73758" style="rich" %}

{% include section.html %}

## All publications

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
