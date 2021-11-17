---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
years: [2021, 2020, 2019]
types: [journal articles, conference papers, posters, preprints]
nav: true
order: 1
---

<div class="publications">

{% for y in page.types %}

  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[type={{y}}]* %}
{% endfor %}

</div>
