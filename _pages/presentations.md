---
permalink: /presentations/
title: "Presentations"
classes: wide
assets_folder: /assets/presentations/
author: cfalguiere
header:
  image: /assets/images/page-header.png
---


{% for group in site.data.presentations.groups %}
📁 {{ group.name }}

  {% for item in group.items %}

  {% if item.relative_url  %}
    {% capture url %} http://cfalguiere.github.io/Presentations/{{ item.relative_url }}{% endcapture %}
  {% else %}
    {% assign url = item.url %}
  {% endif %}

  <a href="{{ url }}" target="blank">{{ item.name }}</a> <span style="font-size: 0.7em">{{ item.lang }}  {{ item.year }}</span>

  {% endfor %}

{% endfor %}
