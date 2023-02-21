---
title: members
permalink: /members/
---
<style>
h1{
  text-align: center;
  font-size: 50px;
  font-family: 'Optimus Princeps';
  font-weight: 100;
  color: #fff;
  margin-top: 50px;
  margin-bottom: 50px;
}
table{
  display: flex;
  justify-content: center;
  align-items: center;
}
 th, tr, td {
  padding: 15px;
  }

</style>


<h1> Gente que se hizo la no hit </h1>

<table>
  <tr>
    <th>Nombre</th>
    <th>Juego 1</th>
    <th>Juego 2</th>
  </tr>
  {% for persona in site.data.personas %}
    <tr>
    <td>{{ persona.nombre }}</td> 
    <td>{{ persona.juego }}</td>
    <td>{{ persona.juego2 }}</td>
    </tr>
  {% endfor %}
</table>