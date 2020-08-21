---
layout: page
title: Schede di allenamento
---

## Ultime schede

<ul>
  {% for post in site.categories.schede %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<!--
## Per tag

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      {% if post.categories[0] == 'schede' %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>
{% endfor %}
-->
