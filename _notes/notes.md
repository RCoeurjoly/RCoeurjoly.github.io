
---
layout: default
title: My notes
---

{% for notes in site.notes %}

<a href="{{ notes.url | prepend: site.baseurl }}">
  <h2>{{ notes.title }}</h2>
</a>

<p class="post-excerpt">{{ notes.description | truncate: 160 }}</p>

{% endfor %}
