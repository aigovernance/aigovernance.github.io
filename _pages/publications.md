---
layout: page
permalink: /accepted/
title: AIGOV-25 Program
years: [2025]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->

<div class="publications">

{%- for y in page.years %}

<!--h2 class="year">{{y}}</h2-->

  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
