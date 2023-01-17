---
layout: page
title: "My notes"
permalink: "/notes/"
---

{% for note in site.notes %}
  <h2>
    <a href="{{ note.url }}">
    </a>
  </h2>
{% endfor %}
