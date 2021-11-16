---
layout: single
title: Mis publicaciones de carácter docente
permalink: /docencia
toc: true
---

{%- for post in site.categories["docencia"] %}
* [{{post.title}}]({{post.url}})
{%endfor %}