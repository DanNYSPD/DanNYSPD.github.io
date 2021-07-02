---
layout: page
permalink: /publications/
title: publications
description: Experience reversed chronological order.
years: [2020,1956, 1950, 1935, 1905]
nav: true
---

<div class="publications">
<!-- Here a iteration is make over the file *.bib, it makes a query for the year -->
{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
