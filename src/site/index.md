---
title: Welcome
layout: layouts/base.njk
---

Welcome to Columbia Business School’s Web Project Blog, your source for updates on the school’s ongoing website overhaul. Check back here for regular updates on what we’re working on, what we’re thinking about, what’s ahead and what it all means for our community.

## Latest Updates

<ul class="listing">
{%- for page in collections.updates | reverse -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>