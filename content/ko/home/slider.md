---
widget: slider
headless: true
weight: 20
content:
  slides:
    - title: <span style="font-size:70%">정보보안</span>
      content: <span style="font-size:70%">중요해지고 있는 정보보안 및 사이버 보안</span>
      align: center
      background:
        image:
          filename: security.jpg
          filters:
            brightness: 0.4
          # assets 폴더에서 이미지를 불러오기 위한 Hugo 함수
          image_src: "{{ .Page.Resources.GetMatch \"media/security.jpg\" }}"
        position: center
        color: '#1dc6f5'
      link:
        icon: user
        icon_pack: fas
        text: <span style="font-size:60%">Join Us</span>
        text-color: '#154ed4'
        url: contact

    - title: <span style="font-size:70%">AI</span>
      content: <span style="font-size:70%">비전/데이터마이닝 분야에 적용 가능한 AI 기술 개발</span>
      align: center
      background:
        image:
          filename: AI1.jpg
          filters:
            brightness: 0.5
          image_src: "{{ .Page.Resources.GetMatch \"media/AI1.jpg\" }}"
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
          image_src: "{{ .Page.Resources.GetMatch \"media/forensic.jpg\" }}"
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
          image_src: "{{ .Page.Resources.GetMatch \"media/mathematics1.jpg\" }}"
        position: center
        color: '#bd4646'

design:
  slide_height: '600px'
  slide_width: '100px'
  is_fullscreen: false
  loop: true
  interval: 3000
---

