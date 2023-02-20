---
title: members
permalink: /members
---

## Gente que se hizo la no hit

<table>
  <tr>
    <th>Nombre</th>
    <th>Juego 1</th>
    <th>Juego 2</th>
  </tr>
  {% for persona in site.data.personas %}
    <tr>
    <td> {{ persona.nombre }} </td> 
    <td>{{ persona.juego }}</td>
    <td>{{ persona.juego2 }} </td>
    </tr>
  {% endfor %}