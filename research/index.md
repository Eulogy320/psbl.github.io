---
title: Research
nav:
  order: 1
  tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

This section presents peer-reviewed articles, reviews, and conference contributions produced by PSBL's members. The list combines the publications in Rodrigo Gutiérrez's CV with the historical publication list from VirtualPlant, removing duplicates. These publications reflect our interdisciplinary research in plant development, computational biology, quantitative modeling, and document our scientific contributions to understanding plant growth, structure, and adaptive processes.

{% assign publication_count = site.data.citations | size %}
<div class="publication-count" aria-label="{{ publication_count }} publications in Research">
  <span class="publication-count-number">{{ publication_count }}</span>
  <span class="publication-count-label">publications</span>
</div>

{% include section.html %}

## Highlighted

{% include citation.html lookup="doi:10.1002/ece3.73758" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
