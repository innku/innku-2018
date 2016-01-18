---
layout: section
title: Contacto | INNKU
permalink: /contact.html
---

{% for contact in site.data.contact.contact %}
<div class="row innku-title">
  <div class="col-lg-12">
    <h1>{{ contact.title }}</h1>
  </div>
  <div class="col-lg-offset-5 col-lg-2 col-md-offset-5 col-md-2 col-sm-offset-5 col-sm-2 col-xs-offset-4 col-xs-4">
    <div class="row">
      <div class="col-lg-offset-4 col-lg-4 col-md-offset-4 col-md-4 col-sm-offset-4 col-sm-4 col-xs-offset-4 col-xs-4 innku-title-divisor">
      </div>
    </div>
  </div>
</div>

<div class="row contact">
  <div class="col-lg-8 col-lg-offset-2">
    <p>{{ contact.description }}</p>
    <div class="redes text-center">
      <a href="https://github.com/innku">github</a>
      <span class="divider"> | </span>
      <a href="https://twitter.com/innku">twitter</a>
      <span class="divider"> | </span>
      <a href="https://www.facebook.com/innku/">facebook</a>
      <span class="divider"> | </span>
      <a href="https://www.linkedin.com/company/innku">linkedin</a>
    </div>
  </div>
</div>
{% endfor %}
