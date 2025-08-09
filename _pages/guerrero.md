---
title: "El camino del guerrero"
permalink: /guerrero/
layout: single
author_profile: true
---

<h2>Introducción</h2>
<p>
Pagina en construcción
> Relatos de poder - Carlos Castaneda.
</p>

<h2>Artículos</h2>
<ul>
{% for post in site.posts %}
  {% if post.tags contains "guerrero" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> <small>({{ post.date | date: "%d-%m-%Y" }})</small></li>
  {% endif %}
{% endfor %}
</ul>