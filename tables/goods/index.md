---
layout: page
title: Goods
---

All Goods
=========

<ul>
  {% for goods_class in site.data.goods %}
    {% for itm in goods_class[1] %}
      <li>{{ itm }}</li>
    {% endfor %}
  {% endfor %}
</ul>
