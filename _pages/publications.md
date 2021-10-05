---
layout: page
permalink: /publications/
title: publications
description:
years: [2022, 2021, 2020, 2019, 2018]
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
