---
# Leave the homepage title empty to use the site title
title:

type: landing

sections:

  - block: hero
    content:
      title: 프로그래밍 언어
      text: 다양한 프로그래밍 언어에 대한 지식을 소개합니다.
    design:
      # --- height 값을 vh 대신 px로 변경하여 고정 높이를 설정합니다 ---
      height: "400px"
  
      # 텍스트가 위아래에 너무 붙지 않도록 적절한 여백을 줍니다.
      spacing:
        padding: ["80px", "0", "80px", "0"]
  
      background:
        image: "learn-language.jpg"
        image_darken: 0.6
        image_size: cover
        image_position: center
  
      text_color_light: true

  - block: collection
    content:
      id: section-1
      title: 가능한 언어
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: language
    design:
      view: custom_card
      columns: '3'
      css_class: justify-text
---
