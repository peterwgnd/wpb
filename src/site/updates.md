---
title: The Latest Updates
layout: layouts/base.njk
---

<ul class="listing">
{%- for page in collections.updates | reverse -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>