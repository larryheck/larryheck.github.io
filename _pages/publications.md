---
layout: page
permalink: /publications/
title: publications
subtitle: <a href='https://scholar.google.com/citations?user=33ZWJmEAAAAJ&hl=en'>Google Scholar</a>
description: Please see my <u><a href='https://scholar.google.com/citations?user=33ZWJmEAAAAJ&hl=en'>Google Scholar</a></u> page
years: 
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
