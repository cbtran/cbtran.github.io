---
layout: page
permalink: /publications/
title: Publications
description:  <span  class="font-weight-bold"><a href="https://scholar.google.com">My Google Scholar Profile</a></span>
years: [2021]
nav: true
---

<div class="publications">

{% for y in page.years %}
  <h5 class="year">{{y}}</h5>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
