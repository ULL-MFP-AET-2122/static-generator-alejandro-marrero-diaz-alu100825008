---
title: "Mostrando datos en la web"
---

La información de las personas que tenemos en nuestro grupo es la siguiente.

<table>
  {% for row in site.data.authors %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
     {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>

