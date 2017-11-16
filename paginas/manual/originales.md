---
layout: page-fullwidth
show_meta: false
title: "Aplicaciones originales"
subheadline: "Aplicaciones propias de Deepin"
header:
   image_fullwidth: "hot.jpg"
permalink: "/originales/"
---
<div class="row t60">
    <div class="medium-6 columns b30">
      <ul>
          {% for post in site.tags.originales %}
          <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
          {% endfor %}
      </ul>
    </div><!-- /.medium-6.columns -->

    <div class="medium-6 columns b30">
      Está listado contiene páginas relacionadas con "Dudas". A diferencia de los tips, están estructuradas en preguntas y respuestas. Es similar a preguntas más frecuentes.

      Explora más en el <a href="{{ site.url }}{{ site.baseurl }}/blog/archive/">Archivo</a>, la <a href="{{ site.url }}{{ site.baseurl }}/introduccion/">Introducción</a> o la sección <a href="{{ site.url }}{{ site.baseurl }}/info/">Información</a>.

    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->
