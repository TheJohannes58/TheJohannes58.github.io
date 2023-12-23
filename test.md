---
layout: default
title: "Test"
---

{% if site.show_excerpts %}
  {% include test.html %}
{% else %}
  {% include meta.html title="Posts" %}
{% endif %}
