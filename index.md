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
feature_row:
  - image_path: /assets/images/2023-annual-meeting.jpg
    alt: "annual meeting"
    title: "PAGK meeting 2023"
    excerpt: '대전 기초과학연구원과학문화센터'
    url: "/annual meeting"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/posts/2020-11-27-photos/2020.jpg
    alt: "Photos"
    title: "Photos"
    excerpt: ''
    url: "/photos"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="registration" type="center" %}
{% include feature_row id="contact" type="center" %}