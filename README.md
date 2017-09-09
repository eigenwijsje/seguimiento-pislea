{% feed_meta %}

# Software Privativo en las licitaciones de la administración pública en Bolivia

Este sitio hace un seguimiento al Plan de Implementación de Software 
Libre y Estándares Abiertos.

Este es un listado de licitaciones publicadas en el sistema de contrataciones
estatales para la administración pública que requieren software privativo.

Los datos están basados en los sitios del [SICOES](https://www.sicoes.gob.bo/) e [INFOSICOES](http://www.sicoes.com.bo/).

- 4 de septiembre, [17-0313-00-768641-3-1](17-0313-00-768641-3-1)
- 1 de septiembre, [17-1701-00-774423-1-1](17-1701-00-774423-1-1)
- 31 de agosto, [17-1701-00-775393-1-1](17-1701-00-775393-1-1)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | absolute_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
