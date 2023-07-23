---
layout: page
permalink: /publications/
title: Publications
description:
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012]
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