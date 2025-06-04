---
layout: default
title: Conteúdos
permalink: /conteudos/
---

<h1>Conteúdos por Categoria</h1>

<h2>Desenvolvimento</h2>
<ul>
  {% for item in site.desenvolvimento %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
</ul>