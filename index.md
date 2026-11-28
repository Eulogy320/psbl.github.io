---
title: Home
---

<section class="home-hero">
  <div class="home-hero-copy">
    <p class="eyebrow">PLANT SYSTEMS BIOLOGY LAB · PUCHILE</p>
    <h1>Understanding how plants sense, signal, and grow.</h1>
    <p class="home-hero-lede">Using <em>Arabidopsis thaliana</em> as a model, we study how nutrient signals interact with genetic, hormonal, and environmental networks to coordinate plant development and adaptation.</p>
    <div class="home-hero-actions">
      {% include button.html link="research" text="Explore our research" icon="fa-solid fa-arrow-right" flip=true %}
      {% include button.html link="publications" text="View publications" icon="fa-solid fa-book-open" style="bare" %}
    </div>
  </div>
  <div class="home-hero-mark">
    <img class="home-hero-logo" src="{{ '/images/logo.png' | relative_url }}" alt="Plant Systems Biology Lab">
  </div>
</section>

{% include section.html full=true %}

{% include figure.html
  image="images/grupal_pic.png"
  link="team"
  width="1182px"
%}

{% include section.html %}

## The lab at a glance

{% capture text %}

Our laboratory integrates experimental plant biology, computational modeling, and systems-level analysis to understand how plants perceive and respond to environmental signals. By combining molecular genetics, quantitative approaches, and theoretical frameworks, we aim to uncover regulatory mechanisms that control growth, adaptation, and resilience.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Our projects address fundamental and applied questions in plant and ecosystem biology, with a focus on growth regulation, environmental adaptation, and resilience to biotic and abiotic stress. By combining molecular genetics, quantitative modeling, synthetic biology, and data-driven approaches, we generate predictive frameworks and actionable knowledge relevant to sustainable agriculture and environmental management.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects-systems-biology.png"
  link="projects"
  title="Our Projects"
  badge="images/psbl-virtualplant-logo.png"
  flip=true
  style="bare"
  text=text
%}


{% capture text %}

Our team is an interdisciplinary group of researchers with expertise in plant biology, genomics, systems biology, computational modeling, and bioinformatics. We foster a collaborative and inclusive research environment that integrates experimental and theoretical approaches, supports early-career scientists, and promotes scientific excellence through training, mentorship, and international collaboration.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/grupal_pic.png"
  link="team"
  title="Our Team"
  badge="images/logo.png"
  text=text
%}
