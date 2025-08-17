---
title: "Camino del guerrero"
permalink: /guerrero/
layout: archive
author_profile: true
entries_layout: list
---

{% assign ordered = site.posts | sort: "date" | reverse %}
{% for post in ordered %}
  {% if post.tags contains "guerrero" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

