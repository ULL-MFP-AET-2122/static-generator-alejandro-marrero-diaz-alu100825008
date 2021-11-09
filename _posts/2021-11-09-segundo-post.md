---
title: "Otro nuevo post"
alumnos: 20
chuchu: 4
esmartes: true
---

# {{ page.title }}

![](https://c.tenor.com/5ety3Lx3QccAAAAC/its-fine-dog-fine.gif)

Todavía es martes. Somos {{ page.alumnos }} alumnos. 

La respuesta a cuánto vale chuchu es {{ page.chuchu }}.

{% if page.esmartes %}
    
## Menudo calvario, aún es martes.
![](https://bestlifeonline.com/wp-content/uploads/sites/3/2019/07/Tuesday-Memes-10.jpg?quality=82&strip=all)
{% else %}

  ## Bueno ya queda menos.
{% endif %}