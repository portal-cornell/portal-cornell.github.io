---
layout: page
permalink: /publications/
title: Publications
description:
years: [2025, 2024, 2023, 2022, 2021, 2020]
nav: true
nav_loc: 4
---
<div class="publications">

<!-- all pubs sorted by year -->
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>