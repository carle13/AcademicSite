---
layout: page
permalink: /publications/
title: publications
description: So far not a peer-reviewed publication, just a reference to the lasp2 project.
years: [2022,2023]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
