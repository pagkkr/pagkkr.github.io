---
title: "Federated ADMET Model"
header:
  teaser: "/assets/presentations/2024-S1-1.png"
  image: "/assets/presentations/2024-S1-1.png"
categories: ["presentations"]
date: "2024-12-18 1:00:00"
date_end: "2024-12-18 1:30:00"
authors : ["Hwa Jong Kim"]
tags: ["deep_learning", "PAGK_2024"]

---
{% assign date_format = "%Y-%m-%d %H:%M" %}
<p class="page__date">
  <strong><i class="fas fa-fw fa-calendar-alt" aria-hidden="true"></i>start:</strong> 
  <time class="dt-published" datetime="{{ page.date}}">{{ page.date | date: date_format }}</time>
  <br>
  <strong><i class="fas fa-fw fa-calendar-alt" aria-hidden="true"></i>end: </strong> 
  <time class="dt-published" datetime="{{ page.date_end}}">{{ page.date_end | date: date_format }}</time>
</p>

# Presenter
{% for author in page.authors %}
{{author}} 
{% endfor %}


# Event
PAGK Annual Meeting 2024

[Document](/assets/presentations/2024-S1-1.pdf){: .btn .btn--primary}
