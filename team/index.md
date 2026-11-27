---
title: Lab Members

nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Plant System Biology Laboratory (PSBL) is an interdisciplinary research group focused on understanding plant development, physiology, and adaptation through the integration of experimental biology, computational modeling, and bioinformatics. The team brings together researchers with expertise in plant molecular biology, genetics, systems biology, and quantitative analysis, fostering a collaborative environment that bridges theory and experimentation. Our members work across multiple scales—from genes and cells to tissues and whole plants—to investigate how biological, mechanical, and environmental signals are integrated during plant growth and morphogenesis. By combining advanced imaging, computational approaches, and mathematical modeling, the laboratory aims to generate predictive frameworks that advance both fundamental plant science and applied research.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="name == 'Rodrigo Gutierrez'" sort="order" %}
{% include list.html data="members" component="portrait" filter="name != 'Rodrigo Gutierrez'" sort="order" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
