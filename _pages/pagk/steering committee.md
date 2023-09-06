---
layout: single
title: "Steering Committee"
permalink: /pagk/steering-committee
sidebar:
  title: "PAGK"
  nav: pagk
---
{% assign authors = '' | split: '' %}
{% for obj in site.data.authors%}
  {% assign authors = authors | push: obj[1] %}
{% endfor %}
{% assign authors = authors | sort: 'name' %}


<div class="entries-grid">
  {% assign presidents = authors | where : "member_group", "president" %}
  {% for author in presidents %}
    <div class="grid__item">
      {% include author-profile.html author=author.id %}
    </div>
  {% endfor %}
  {% assign members = authors | where : "member_group", "member" %}
  {% for author in members %}
    <div class="grid__item">
      {% include author-profile.html author=author.id %}
    </div>
  {% endfor %}
</div>