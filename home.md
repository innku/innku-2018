---
layout: home
title: Home | INNKU
permalink: /home.html
---

<div class="row home">

  <div id="innku-projects" class="section_innku">
    <div class="col-lg-offset-3 col-lg-6 text-center title">
      <h1>Generamos negocios en internet enfocados en resultados</h1>
      <div class="divider"></div>
    </div>
    <div class="col-lg-12 arrow">
      <a href="#destiny" class="bounce">
        <img src="img/home/arrow.png" alt="arrow">
      </a>
    </div>
  </div>

  <div id="reserbus" class="section reserbus">
    {% for proyects in site.data.proyects.reserbus %}
      <div id="destiny" class="info-top">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_top_content">
          <h1>{{ proyects.title }}</h1>
        </div>
      </div>
      <div class="info">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_content">
          <img src="{{ proyects.logo }}" alt="{{ proyects.proyect }}" />
          <p>{{ proyects.description }}</p>
          <a href="{{ proyects.site }}" class="btn btn-innku" role="button" target="_blank">Visita el sitio</a>
          <br class="visible-xs">
          <a href="{{ proyects.appstore }}" class="btn btn-innku" role="button" target="_blank">Descarga la app para iOS</a>
          <br class="visible-xs">
          <a href="{{ proyects.android }}" class="btn btn-innku" role="button" target="_blank">Descarga la app para Android</a>
        </div>
      </div>
    {% endfor %}
  </div>

  <div id="rutanet" class="section rutanet">
    {% for proyects in site.data.proyects.rutanet %}
      <div class="info-top">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_top_content">
          <h1>{{ proyects.title }}</h1>
        </div>
      </div>
      <div class="info">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_content">
          <img src="{{ proyects.logo }}" alt="{{ proyects.proyect }}" />
          <p>{{ proyects.description }}</p>
          <a href="{{ proyects.site }}" class="btn btn-innku" role="button" target="_blank">Visita el sitio</a>
        </div>
      </div>
    {% endfor %}
  </div>

  <div id="disculpe-doctor" class="section disculpe_dr">
    {% for proyects in site.data.proyects.disculpe_doctor %}
      <div class="info-top">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_top_content">
          <h1>{{ proyects.title }}</h1>
        </div>
      </div>
      <div class="info">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_content">
          <img src="{{ proyects.logo }}" alt="{{ proyects.proyect }}" />
          <p>{{ proyects.description }}</p>
          <a href="{{ proyects.site }}" class="btn btn-innku" role="button" target="_blank">Visita el sitio</a>
          <br class="visible-xs">
          <a href="{{ proyects.appstore }}" class="btn btn-innku" role="button" target="_blank">Descarga la app para iOS</a>
          <br class="visible-xs">
          <a href="{{ proyects.android }}" class="btn btn-innku" role="button" target="_blank">Descarga la app para Android</a>
        </div>
      </div>
    {% endfor %}
  </div>

  <div id="aventones" class="section aventones">
    {% for proyects in site.data.proyects.aventones %}
      <div class="info-top">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_top_content">
          <h1>{{ proyects.title }}</h1>
        </div>
      </div>
      <div class="info">
        <div class="col-lg-offset-1 col-lg-10 col-md-12 info_content">
          <img src="{{ proyects.logo }}" alt="{{ proyects.proyect }}" />
          <p>{{ proyects.description }}</p>
          <a href="{{ proyects.site }}" class="btn btn-innku" role="button" target="_blank">Visita el sitio</a>
        </div>
      </div>
    {% endfor %}
  </div>

</div>
