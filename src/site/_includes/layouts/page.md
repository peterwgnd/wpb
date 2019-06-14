---
layout: layouts/base.njk
pageClass: page
templateEngineOverride: njk, md
---


<article>
<header>
<h1>{{ title }}</h1>
{%- if subtitle %}<p class="subtitle">{{ subtitle }}</p>{% endif %}
</header>
<main>
  {{ content | safe }}
</main>
</article>
