---
# Leave the homepage title empty to use the site title
title: 학습 교과

type: landing

sections:

  - block: hero
    content:
      # 배경 위에 표시될 텍스트를 여기에 입력합니다.
      title: '학습 교과'
      text: '다양한 학습 내용을 소개합니다.'

    design:
      # --- 이 부분을 추가하여 이미지를 배경으로 설정합니다 ---
      background:
        # assets/media/ 폴더에 있는 이미지 파일을 배경으로 지정
        filename: 'study.jpg'

        # 이미지가 위젯 크기에 맞춰 공백 없이 꽉 채우도록 설정
        image_size: cover

        # 이미지가 잘릴 경우 중앙을 기준으로 표시
        image_position: center

        # 이미지 위에 덮을 반투명 레이어 (선택 사항)
        image_darken: 0.5

      # 배경이 어두우므로 텍스트 색상을 밝게 설정
      text_color_light: true

      # 배너의 높이를 지정 (원하는 값으로 조절)
      height: "400px"

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">관심 분야</span>
      text: <br><br>
      items:
        - name: 인공지능
          icon: cogs
          icon_pack: fas
          description: <span style="font-size:90%">데이터 분석 및 지능형 시스템 구축을 위한 머신러닝 기술 연구 및 적용</span><br><br>

        - name: 알고리즘
          icon: code-branch
          icon_pack: fas
          description:  <span style="font-size:90%">효율적인 문제 해결을 위한 자료구조 및 알고리즘 설계</span><br><br>

        - name: 개발
          icon: code
          icon_pack: fas
          description:  <span style="font-size:90%">안정적이고 확장 가능한 웹/앱 서비스 개발 및 소프트웨어 아키텍처 설계</span><br><br>

        - name: 컨텐츠
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">사용자 경험(UX)에 기반한 창의적인 인터랙티브 콘텐츠 기획 및 제작</span><br><br>

        - name: 네트워크
          icon: wifi
          icon_pack: fas
          description:  <span style="font-size:90%">분산 시스템 및 안정적인 서비스 통신을 위한 네트워크 프로토콜 이해</span><br><br>

        - name: 보안
          icon: shield-alt
          icon_pack: fas
          description:  <span style="font-size:90%">시스템 취약점 분석 및 시큐어 코딩을 통한 견고한 소프트웨어 보안 구축</span><br><br>

  - block: collection
    content:
      id: section-1
      title: 학습
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
      page_type: class
    design:
      view: custom_card
      columns: '3'
      css_class: justify-text
---
