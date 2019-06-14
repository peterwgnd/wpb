---
title: Latest Updates
layout: layouts/listpage.md
bodyClass: list-page
description: The latest updates on Columbia Business School’s Web Project.
---

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