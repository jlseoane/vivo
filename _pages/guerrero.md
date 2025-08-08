---
title: "El camino del guerrero"
permalink: /guerrero/
layout: single
classes: wide
author_profile: true
---
Página en construcción. En esta página encontrarás una introducción al camino del guerrero en la tradición tolteca, así como artículos que desarrollan sus principios fundamentales.

---

{% include base_path %}
{% assign posts_guerrero = site.posts | where_exp: "post", "post.tags contains 'guerrero'" %}
{% for post in posts_guerrero %}
  {% include archive-single.html %}
{% endfor %}