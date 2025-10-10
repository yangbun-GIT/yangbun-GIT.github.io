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

  - block: slider
    content:
      slides:

        - title: <span style="font-size:70%">정보보안</span>
          content: <span style="font-size:70%">중요해지고 있는 정보보안 및 사이버 보안</span>
          align: center
          background:
            image:
              filename: security1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#1dc6f5'
          link:
            icon: user
            icon_pack: fas
            text: <span style="font-size:60%">Join Us</span>
            text-color: '#154ed4'
            url: contact

        - title: <span style="font-size:70%">AI</span>
          content: <span style="font-size:70%">비전/데이터마이닝 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
          align: center
          background:
            image:
              filename: Ai1.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#d346e3'

        - title: <span style="font-size:70%">디지털포렌식</span>
          content: <span style="font-size:70%">사이버수사대 디지털포렌식 중요도 증가</span>
          align: center
          background:
            image:
              filename: forensic.jpg
              filters:
                brightness: 0.3
            position: center
            color: '#7986ba'

        - title: <span style="font-size:70%">Math</span>
          content: <span style="font-size:70%">데이터마이닝 및 AI 활용 수학 연구</span>
          align: center
          background:
            image:
              filename: mathematics1.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#bd4646'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '600px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

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
