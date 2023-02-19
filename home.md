---
title: Pagina principal
permalink: /
---

# Bienvenido a {{page.title}} de {{site.title}} 

### Paginas:
<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{page.url}}">{{page.title}}</a>
      {% if page.children.size > 0 %}
        <ul>
          {% for child in page.children %}
              <li><a href="{{child.url}}">{{ child.title }}</a></li>
          {% endfor %}
        </ul>
      {% endif %}
    </li>
  {% endfor %}
</ul>


### Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

![Image](/assets/img/Fromsoftwaregames.png)
