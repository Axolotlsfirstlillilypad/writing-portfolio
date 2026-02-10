---
layout: default
title: "Writing Portfolio"
---

# Welcome to My Writing Portfolio

Here’s a collection of my works:

{% for post in site.works %}
- [{{ post.title }}]({{ post.url }})  
  ![Thumbnail]({{ post.thumbnail }})
{% endfor %}
