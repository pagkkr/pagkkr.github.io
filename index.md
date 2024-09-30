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
top:
  - image_path_temp: "/assets/annual-meeting/pagk-annual-meeting-2023.png"
    alt: "annual meeting"
    title: "PAGK Annual Meeting 2024"
    excerpt: "장소: 서울대병원 의생명연구원 1층 우덕 윤덕병 홀<br>
시간: 2024년 12월 18일(수) 오후"
    url: "/posts/2024-09-19-annual-meeting"
    btn_label: "더보기"
    btn_class: "btn--primary"
annual_meeting_registration:
  - title: "PAGK Annual Meeting 2024 등록"
    excerpt: "1차 마감: 2024년 11월 15일 23:59"
    url: "https://forms.gle/PwuUYZC4SQ4j4GKo7"
    btn_label: "등록"
    btn_class: "btn--primary"
annual_meeting_preworkshop_registration:
  - title: "PAGK Annual Meeting 2024 사전 워크샵 등록"
    excerpt: "추후 공지"
    url: "https://forms.gle/"
    btn_label: "추후 공지"
    btn_class: "btn--primary"
photos:
  - image_path: /assets/posts/2023-12-11-annual_meeting_photos/2023-12-11-01.jpg
    alt: "Photos"
    title: "Photos"
    excerpt: ''
    url: "/photos"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
<!-- 필요하면 주석처리 해제 -->
{% include feature_row id="top" type="center" %}
{% include feature_row id="annual_meeting_registration" type="center" %}
{% include feature_row id="photos" type="center" %}
{% include feature_row id="registration" type="center" %}
{% include feature_row id="contact" type="center" %}
