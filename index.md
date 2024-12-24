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
    excerpt: pagk2006@gmail.com
top:
  - image_path_temp: "/assets/annual-meeting/pagk-annual-meeting-2023.png"
    alt: "annual meeting"
    title: "PAGK Annual Meeting 2024"
    excerpt: '발표자료는 취합 중입니다. 현재까지 취합된 발표자료는 <br> <a href="https://pagk.kr/presentations">Presentations</a>에서 열람하실 수 있습니다. <br>감사합니다.'
    url: "/presentations"
    btn_label: "더보기"
    btn_class: "btn--primary"
annual_meeting_registration:
  - title: "PAGK Annual Meeting 2024 등록"
    excerpt: "3차 마감: 2024년 12월 15일 23:59"
    url: "https://forms.gle/PwuUYZC4SQ4j4GKo7"
    btn_label: "등록"
    btn_class: "btn--primary"
annual_meeting_preworkshop_registration:
  - title: "PAGK Annual Meeting 2024 사전 워크샵 등록"
    excerpt: " "
    url: "https://docs.google.com/forms/d/e/1FAIpQLSeGhLhDevtx2GaUycCfY1496sDd3OS17PP0ANmWQvQWTW1Uiw/viewform"
    btn_label: "등록"
    btn_class: "btn--primary"
photos:
  - alt: "Photos"
    title: "Photos"
    excerpt: ''
    url: "/photos"
    btn_label: "Read More"
    btn_class: "btn--primary"
    image_path_사진_필요하면_image_path만_남기면_작동함: /assets/posts/2023-12-11-annual_meeting_photos/2023-12-11-01.jpg
---
<!-- 이게 주석 -->
<!-- 필요하면 주석처리 해제 -->
{% include feature_row id="top" type="center" %}
<!-- {% include feature_row id="annual_meeting_registration" type="center" %} -->
<!-- {% include feature_row id="annual_meeting_preworkshop_registration" type="center" %} -->
{% include feature_row id="photos" type="center" %}
{% include feature_row id="registration" type="center" %}
{% include feature_row id="contact" type="center" %}
