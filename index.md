---
title: Blog - 2020
layout: layout.liquid
pagination: 
    data: collections.blog
    size: 2
    alias: blogs
---

A collection of thoughts about various things, mostly in an attempt to etch them into my memory, or at least refer back to when my memory fails me. It'll be learnings, great and small, about coding and various other things plus what I'm reading, watching or hearing. 

{% for blog in blogs %}

- [{{blog.data.title}}]({{blog.url}})

{% endfor %}

{% if pagination.href.previous %} <a href="{{pagination.href.previous}}">Previous Page</a> {% endif %}
{% if pagination.href.next %} <a href="{{pagination.href.next}}">Next Page </a> {% endif %}