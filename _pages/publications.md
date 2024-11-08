---
layout: page
permalink: /publications/
title: Publications
description: All of my publications are available at Uliège institutional repository ORBi.
years_papers: [2024, 2023]
years_conf: [2024, 2023, 2021]
nav: true
nav_order: 1
---

## Journal articles
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years_papers %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

## International Conferences
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years_conf %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conf -q @*[year={{y}}]* %}
{% endfor %}

</div>
