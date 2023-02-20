---
title: "Posts"
layout: posts
permalink: /posts/
author_profile: true
---


<nav class="pagination">
  {% if paginator.previous_page %}
    <a href="{{ paginator.previous_page_path }}">Más nuevo</a>
  {% endif %}

  {% if paginator.next_page %}
    <a href="{{ paginator.next_page_path }}">Más antiguo</a>
  {% endif %}
</nav>
