---
title: "El camino del guerrero"
permalink: /guerrero/
layout: single
author_profile: true
---

## Introducción
> “En el corazón de la antigua sabiduría mesoamericana, el guerrero no es quien empuña un arma, sino quien vence a su propio miedo.”

El pueblo y la cultura tolteca tuvo su auge entre los siglos VIII y XII, y se asentó en la zona meridional de México (también conocida como mesoamérica), desde dónde influyó notablemente en la civilización azteca. Fue la matriz espiritual de aquella zona, mucho antes de la colonización española.

La expresión "tolteca"  en aquella lengua significa "artista", pero también "hombre de conocimiento", y eran los llamados “naguales” (podríamos traducirlo como chamanes) los encargados de custodiar generación tras generación, el conocimiento espiritual de esa cultura.

Ya en el siglo XX escritores tales como Miguel Ruiz y Carlos Castaneda investigaron acerca de esa cultura y del significado que se escondía tras la expresión "hombre de conocimiento", y la condensaron en lo que popularmente tomó el nombre de **El camino del guerrero**.

Ante todo, el camino del guerrero no es un sendero de violencia, no hay lucha exterior; todo lo contrario, es un camino hacia el autodominio y la toma de conciencia. Sus armas son el control, la disciplina, la impecabilidad, el silencio interior, la responsabilidad de tu propia vida. Todos ellos son principios que ensalzan la calidad humana.

Usar esas armas con maestría es el objetivo de ese camino. El caminante tendrá que aprender a ser  disciplinado, luchar a diario contra sí mismo, contra sus temores y debilidades, actuar con conciencia, liberarse de ataduras que le limitan. Como puedes intuir, se trata de un trabajo introspectivo, que puede llegar a ser fascinante.

![guerrero-samurai.png](/vivo/assets/images/guerrero-samurai.jpg)

Este espacio es una muestra y a la vez una invitación para que recorras  un sendero que conduce a la maestría personal. **El camino del guerrero no es para todos, pero todo aquel que lo elige, se transforma.**

> *En la vida del guerrero sólo hay una cosa, un único asunto que en realidad no está decidido: qué tan lejos puede uno avanzar en la senda del conoci­miento y el poder.*
> 
> Relatos de poder - Carlos Castaneda.
---

## Artículos relacionados

{% for post in site.posts %}
  {% if post.tags contains "guerrero" %}
  - [{{ post.title }}]({{ post.url | relative_url }}) <small>({{ post.date | date: "%d-%m-%Y" }})</small>
  {% endif %}
{% endfor %}