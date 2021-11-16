---
layout: single
title: Mis publicaciones personales en el blog
permalink: /blog
toc: true
---

{%- for post in site.categories["blog"] %}
* [{{post.title}}]({{post.url}})
{%endfor %}