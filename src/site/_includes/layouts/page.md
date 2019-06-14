---
layout: layouts/base.njk
pageClass: page
templateEngineOverride: njk, md
---

<main>
<article>
<header>
<h1>{{ title }}</h1>
{%- if subtitle %}<p class="subtitle">{{ subtitle }}</p>{% endif %}
</header>
  {{ content | safe }}
</article>
</main>