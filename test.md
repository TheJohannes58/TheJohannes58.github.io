---
layout: default
title: "Test"
---

{% if site.show_excerpts %}
  {% include test.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
