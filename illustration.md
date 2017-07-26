---
layout: default
title: Illustration
permalink: /illustration/
---

<h1 class="page-heading">Illustration</h1>

<div class="home">

  {% for project in site.portfolioillustration limit:40 %}
  <div class="thumbnail-container col-xs-12 col-md-4">
    <a href="{{ project.url | prepend: site.baseurl }}">
      <div class="thumbnail">
        {% if project.image %}
        <img src="/{{ project.image }}">
        {% endif %}
        <h3>
          <a class="project-link" href="{{ project.url | prepend: site.baseurl }}">{{ project.title }}</a>
        </h3>
        <p>{{ project.short-description }}</p>
      </div>
    </a>
  </div>
  {% endfor %}

</div>