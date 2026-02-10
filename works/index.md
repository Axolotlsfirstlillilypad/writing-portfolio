---
layout: default
title: "All Works"
---

# My Works

<ul>
{% for work in site.works %}
  <li><a href="{{ work.url }}">{{ work.title }}</a></li>
{% endfor %}
</ul>
