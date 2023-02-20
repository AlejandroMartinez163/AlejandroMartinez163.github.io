---
title: Página principal
permalink: /
layout: home
---


### Páginas:

<ul>
  <li>
    <a href="AlejandroMartinez163.github.io/test"> Test</a>
  </li>

  <li>
    <a href="AlejandroMartinez163.github.io/members"> Members</a>
  </li>

  <li>
    <a href="AlejandroMartinez163.github.io/posts"> Posts</a>
  </li>
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
