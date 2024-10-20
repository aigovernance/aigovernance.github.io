---
layout: page
permalink: /ijcai2024/accepted/
title: AIGOV-24 Accepted papers
years: [2024]
nav: true
nav_order: 6
---
<!-- _pages/publications.md -->


<div class="publications">


{%- for y in page.years %}

<!--h2 class="year">{{y}}</h2-->

  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
