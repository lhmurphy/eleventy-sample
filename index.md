---
title: Blog - 2020
layout: layout.liquid
---

A collection of thoughts about various things, mostly in an attempt to etch them into my memory, or at least refer back to when my memory fails me. It'll be learnings, great and small, about coding and various other things plus what I'm reading, watching or hearing. 

{% for blog in collections.blog %}
- [{{blog.data.title}}]({{blog.url}})
{% endfor %}
