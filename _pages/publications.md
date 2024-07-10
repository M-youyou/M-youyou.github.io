---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=7UEqgLcAAAAJ)] || [[View by topic](https://ywzhang.cn/research/)]
 


#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
