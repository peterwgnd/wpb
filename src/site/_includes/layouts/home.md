---
layout: layouts/base.njk
bodyClass: home
templateEngineOverride: njk, md
---

<main>
<header>
<h1>{{ title }}</h1>
<img src="/images/{{ img  }}" alt="{{ imageAlt }}">
</header>
{{ content | safe }}
</main>
