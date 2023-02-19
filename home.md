---
title: Pagina principal
permalink: /
---

# Welcome to {{site.title}} {{page.title}} 

## Paginas:

<ul>
{% for page in site.pages %}
  <li>
    <a href="{{ page.url }}">{{ page.title }}</a>
  </li>
{% endfor %}
</ul>
 

## Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

![Image](/assets/img/logo-jekyll.png)
