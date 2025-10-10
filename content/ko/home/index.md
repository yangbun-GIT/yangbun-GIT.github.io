---
# Homepage
title:
type: widget_page

# Homepage is headless, other widget pages are not.
headless: true

sections:
  - block: about.avatar
    weight: 10
    author: admin
    content:
      text: ""
      description: |
        전북대학교 IT정보공학과(現-컴퓨터인공지능학부)에 재학중인 **윤영준**입니다.  
        저는 현재 3학년 2학기 과정을 수료중입니다.   
        이곳에서 "[소개](/ko/about/)" 저에 대한 정보를 확인할 수 있습니다.

  - block: portfolio
    weight: 20
    content:
      title: ''
      subtitle: ''
      page_type: project
      filter_default: 0
      filter_button:
        - name: All
          tag: '*'
        - name: Machine Learning
          tag: ML
        - name: Computer Vision
          tag: CV
        - name: NLP
          tag: NLP

    design:
      columns: '1'
      view: masonry
      flip_alt_rows: true
      background: {}
      spacing: {padding: [0, 0, 0, 0]}
---
