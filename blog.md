---
layout: section
title: Blog | INNKU
permalink: /blog.html
---

<div class="container blog">
  <section>

    <div class="row">
      <div class="col-md-10 col-md-offset-1 col-xs-12 blog">
        <ul style="list-style-position: inside">
          {% for post in site.posts %}
           <li>
            <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
            <br>
            <span class="date_blog">{{ post.date | date: "%d %B %Y" }}</span>
            <p>{{ post.excerpt }}</p>
           </li>
          {% endfor %}
        </ul>
      </div>
    </div>

  </section>
</div>