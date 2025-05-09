---
layout: page
permalink: /publications/
title: Publications
description: Publications, sorted by the year. 
years: {2021, 2022}
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f {{ site.scholar.bibliography }}  %}
{% endfor %}

</div>
