---
title: Web Policies
layout: layouts/base.njk
---

{%- for page in collections.policy | reverse -%}
  <article>
    <h2><a href="{{ page.url }}">{{ page.data.title }}</a></h2>
    <p>Last updated on <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time></p>
  </article>
{%- endfor -%}