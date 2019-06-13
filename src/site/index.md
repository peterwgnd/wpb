---
title: EleventyOne
subtitle: A project scaffold for getting building with Eleventy quickly.
layout: layouts/base.njk
---


## Latest Updates

<ul class="listing">
{%- for page in collections.updates | reverse -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Links from an external data source

These links were sourced from [hawksworx.com](https://www.hawksworx.com/feed.json) at build time.

<ul class="listing">
{%- for item in hawksworx.entries.slice(0,5) -%}
  <li>
    <a href="{{ item.link }}">{{ item.title }}</a>
  </li>
{%- endfor -%}
</ul>


The data can be stashed locally by running:

```
yarn run seed
```

It will then be available locally for building with:

```
yarn start
```