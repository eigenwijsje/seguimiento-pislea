{% feed_meta %}

# Software Privativo en las licitaciones de la administración pública en Bolivia

Este sitio hace un seguimiento al Plan de Implementación de Software
Libre y Estándares Abiertos.

Este es un listado de licitaciones publicadas en el sistema de contrataciones
estatales para la administración pública que requieren software privativo.

Los datos están basados en los sitios del [SICOES](https://www.sicoes.gob.bo/) e [INFOSICOES](http://www.sicoes.com.bo/).

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | absolute_url }}">{{ post.title }}</a>
	     {{ post.excerpt }}
       Tecnologías:
       <ul>
         {% for tag in post.tags %}
         <li>{{ tag }}</li>
         {% endfor %}
       </ul>
    </li>
  {% endfor %}
</ul>
