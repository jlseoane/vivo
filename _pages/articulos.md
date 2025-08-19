---
title: "Artículos"
permalink: /articulos/
layout: home
author_profile: archive
entries_layout: list
---

**¡Bienvenido a mi blog!**. Aquí encontrarás artículos sobre experiencias de la vida, reflexiones personales y lecturas que me han inspirado.  
También podrás explorar [el camino del guerrero](/vivo/guerrero/), donde comparto enseñanzas y reflexiones relacionadas con una antigua cultura mesoamericana.

Usa los menús superiores para navegar cómodamente entre las secciones.
---

{% for post in site.posts %}
  {% unless post.tags contains "guerrero" %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}