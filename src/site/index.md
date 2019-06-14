---
title: Welcome
layout: layouts/home.md
image: img-perelman-center.jpg
image-alt: Perelman Center
---

Thank you for visiting Columbia Business School’s Web Project Blog, your source for updates on the school’s ongoing website overhaul. Check back here for regular updates on what we’re working on, what we’re thinking about, what’s ahead and what it all means for our community.

<section class="updates">

## Latest Updates

<ul class="listing">
{%- for page in collections.updates | reverse -%}
  <li>
<article class="card">
<img src="{{ page.data.img }}" alt="{{ page.data.imgAlt }}">
<div class="summary">
<h3>
<a href="{{ page.url }}">{{ page.data.title }}</a>
</h3>
<p class="date"><time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time></p>
<p class="dek">{{page.data.description}}</p>
</div>
</article>
</li>
{%- endfor -%}
</ul>

</section>