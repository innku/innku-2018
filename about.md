---
layout: section
title: Acerca de | INNKU
permalink: /about.html
---

{% for about in site.data.about_innku.about %}
  <div class="row innku-title">
    <div class="col-lg-12">
      <h1>{{ about.title }}</h1>
    </div>

    <div class="col-lg-offset-5 col-lg-2 col-md-offset-5 col-md-2 col-sm-offset-5 col-sm-2 col-xs-offset-4 col-xs-4">
      <div class="row">
        <div class="col-lg-offset-4 col-lg-4 col-md-offset-4 col-md-4 col-sm-offset-4 col-sm-4 col-xs-offset-4 col-xs-4 innku-title-divisor">
        </div>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col-lg-6">
      <p>{{ about.column_one }}</p>
    </div>
    <div class="col-lg-6">
      <p>{{ about.column_two }}</p>
    </div>
  </div>
{% endfor %}
