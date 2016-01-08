---
layout: section
title: Equipo | INNKU
permalink: /team.html
---

<div class="row innku-title">
  <div class="col-lg-12">
    <h1>Nuestro equipo</h1>
  </div>

  <div class="col-lg-offset-5 col-lg-2 col-md-offset-5 col-md-2 col-sm-offset-5 col-sm-2 col-xs-offset-4 col-xs-4">
    <div class="row">
      <div class="col-lg-offset-4 col-lg-4 col-md-offset-4 col-md-4 col-sm-offset-4 col-sm-4 col-xs-offset-4 col-xs-4 innku-title-divisor">
      </div>
    </div>
  </div>
</div>

<div class="row team">

  {% for team in site.data.team.abi %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description}}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.adrian %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description}}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.beto %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description}}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

</div>

<div class="row team">

  {% for team in site.data.team.angel %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description}}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.benito %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.furia %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

</div>

<div class="row team">

  {% for team in site.data.team.edith %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.elias %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.gabo %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

</div>

<div class="row team">

  {% for team in site.data.team.george %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.sarait %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

  {% for team in site.data.team.sebas %}
    <div class="col-lg-4 col-sm-4 col-xs-12 text-center member">
      <figure class="effect-oscar">
        <img src="{{ team.image }}">
        <figcaption>
          <h2><span>{{ team.name }}</span> {{ team.last }}</h2>
          <p>{{ team.description }}</p>
        </figcaption>
      </figure>
    </div>
  {% endfor %}

</div>
