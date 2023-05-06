---
layout: default
title: Example post
cover: cover.jpg
date: 
categories: posts
---

## Śpis staronak sajta

{% for p in site.pages %}
{{p.title}}  
{% endfor %}