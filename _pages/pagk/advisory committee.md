---
layout: single
title: "Advisory Committee"
permalink: /pagk/advisory-committee
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
  {% assign advisors = authors | where : "member_group", "advisor" %}
  {% for author in advisors %}
    <div class="grid__item">
      {% include author-profile.html author=author.id %}
    </div>
  {% endfor %}
</div>