---
layout: page
permalink: /research/
title: Research
description: # publications by categories in reversed chronological order. generated by jekyll-scholar.
nav: true
nav_order: 2
scholar:
  bibliography: workingpapers.bib
  query: "@unpublished"
  group_by: year
  group_order: descending
---

<!-- Optional search -->
<!-- {% include bib_search.liquid %} -->

<div class="publications">
  {% bibliography %}
</div>
