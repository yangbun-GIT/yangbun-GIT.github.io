---
# Leave the homepage title empty to use the site title
title:

type: landing

sections:

  - block: hero # 'hero' 블록을 첫 번째 섹션으로 추가
    content:
      title: 
      image:
        # assets/media/ 폴더 안의 이미지 파일
        filename: learn-language.jpg
      text: 

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
