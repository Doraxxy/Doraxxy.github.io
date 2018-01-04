---
layout: archive
title: "信息可视化作品集"
date: 2018-01-04 14:25:45-04:00
modified:
excerpt: "Biong~"
tags: []
image: 
  feature: infovis.jpg
  teaser:
---


<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 visualization 的列出来-->
