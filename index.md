---
layout: splash
header:
  overlay_color: "0000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/front.png
  actions:
    - label: "PAGK 소개"
      url: "/pagk/about"
  caption: 
excerpt: "Population Approach Group in Korea<br>집단 약동 약력학 연구회"
intro: 
  - excerpt: '집단 약동 약력학 연구회'
registration :
  - title: "Sign Up"
    excerpt: 
    url: "https://forms.gle/FvNjHEDHmdgaX2Qt6"
    btn_label: "가입하기"
    btn_class: "btn--primary"
contact :
  - title: "Contact"
    excerpt: 
    url: "https://forms.gle/QFJqyEdAwB478iJa9"
    btn_label: "문의하기"
    btn_class: "btn--primary"
meeting:
  - image_path: "/assets/annual-meeting/pagk-annual-meeting-2023.png"
    alt: "annual meeting"
    title: "PAGK Annual Meeting 2023"
    excerpt: "장소: 대전 기초과학연구원과학문화센터<br>
시간: 12월 11일 (월) 오전 9시 - 오후 5시 30분"
    url: "/posts/2023-09-11-annual-meeting"
    btn_label: "더보기"
    btn_class: "btn--primary"
registration2023:
  - title: "PAGK 2023 등록"
    excerpt: "1차 등록 기한 11월 26일(일) 23:59"
    url: "https://forms.gle/WZF5Rut4YvXHvAFr6"
    btn_label: "등록하기"
    btn_class: "btn--primary"
photos:
  - image_path: /assets/posts/2020-11-27-photos/2020.jpg
    alt: "Photos"
    title: "Photos"
    excerpt: ''
    url: "/photos"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="meeting" type="center" %}
{% include feature_row id="registration2023" type="center" %}
{% include feature_row id="photos" type="left" %}
{% include feature_row id="registration" type="center" %}
{% include feature_row id="contact" type="center" %}
