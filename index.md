---
layout: default
title: アプリ
---

# アプリ

<ul class="app-list">
{% for app in site.data.apps %}
  <li><a href="/apps/{{ app.slug }}/"><img src="{{ app.icon }}" alt=""><div><div class="name">{{ app.name }}</div><div class="tag">{{ app.tagline }}</div></div></a></li>
{% endfor %}
</ul>
