---
title: Web Policies
layout: layouts/listpage.md
bodyClass: list-page
description: Web policies and governance
---

{%- for page in collections.policy | reverse -%}
  <article>
    <h2><a href="{{ page.url }}">{{ page.data.title }}</a></h2>
    <p class="date">Last updated on <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time></p>
  </article>
{%- endfor -%}