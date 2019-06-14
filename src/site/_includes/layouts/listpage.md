---
layout: layouts/base.njk
bodyClass: listpage
templateEngineOverride: njk, md
---

<main>
<header>
<h1>{{ title }}</h1>
{%- if subtitle %}<p class="subtitle">{{ subtitle }}</p>{% endif %}
</header>
  {{ content | safe }}
</main>
