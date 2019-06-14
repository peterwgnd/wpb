---
layout: layouts/base.njk
pageClass: posts
templateEngineOverride: njk, md
---
<header>
	<h1>{{ title }}</h1>
	{%- if subtitle %}<p class="subtitle">{{ subtitle }}</p>{% endif %}
</header>
<p>
   <span class="date"><time datetime="{{ date }}">{{ date | dateDisplay }}</time></span>
</p>
<main>
  {{ content | safe }}
  <div class="footnote">
  </div>
</main>
