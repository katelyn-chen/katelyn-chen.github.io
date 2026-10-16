---
title: Projects
layout: default
permalink: /projects/
excerpt: "Selected engineering and design work: mechatronics, mechanism design, fabrication, and human-centered products."
---

<div class="kc-wrap">
  <header class="kc-page-head">
    <h1>Projects</h1>
    <!-- <p>Selected engineering and design work spanning mechatronics, mechanism design, fabrication, and human-centered products.</p> -->
  </header>

  <div class="kc-projects">
    {% assign projects = site.projects | sort: "path" %}
    {% for p in projects %}
      {% unless p.research_only %}
      {% assign teaser = p.header.teaser | default: p.header.image %}
      <a class="kc-project" href="{{ p.url | relative_url }}">
        <div class="kc-project__img">
          {% if teaser %}<img src="{{ teaser | relative_url }}" alt="{{ p.title | escape }}" loading="lazy">{% endif %}
        </div>
        <div class="kc-project__body">
          <h3>{{ p.title }}</h3>
        </div>
      </a>
      {% endunless %}
    {% endfor %}
  </div>
</div>
