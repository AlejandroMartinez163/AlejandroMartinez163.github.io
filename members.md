---
title: members
permalink: /members
---


# Miembros con posts

{% for member in site.members %}
  <p> {{ member.name }} - {{ member.position }} </p>
  [ver]({{ member.url }}) 

{% endfor %}

## Gente que se hizo la no hit

{% for persona in site.data.personas %}
  
  <p> {{ persona.nombre }} - {{ persona.juego }} {{ persona.juego2 }} </p>
{% endfor %}