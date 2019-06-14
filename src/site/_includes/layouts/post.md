---
layout: layouts/base.njk
pageClass: posts
bodyClass: update
templateEngineOverride: njk, md
---

<main>

<article>
<header>
<h1>{{ title }}</h1>
<p>
   <span class="author">{{ author }}</span>&nbsp;&nbsp;|&nbsp;&nbsp;<span class="date"><time datetime="{{ date }}">{{ date | dateDisplay }}</time></span>
</p>
{%- if subtitle %}<p class="subtitle">{{ subtitle }}</p>{% endif %}
</header>
{%- if img %}<img src="{{ img }}" alt="{{ imgAlt }}">{% endif %}

  {{ content | safe }}

</article>
</main>