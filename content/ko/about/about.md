---
# An instance of the About widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: about
type: widget_page

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: '소개'

# Choose the user profile to display
# This should be the username (folder name) of a profile in your `content/authors/` folder.
# See https://docs.hugoblox.com/get-started/#introduce-yourself
author: admin
---
sections:
  - block: about.avatar
    content:
      username: admin
      text: |
        전북대학교 IT정보공학과(現-컴퓨터인공지능학부)에 재학중인 **윤영준**입니다.  
        A.I에 대한 연구나 A.I를 활용한 어플리케이션 및 컨텐츠 개발에 관심을 가지고 있습니다.  
        현재 3학년 2학기 과정을 수료중으로 이전 학기에 배운 인공지능을 기반으로 지금은 기계학습과 데이터마이닝에 대해 배우고 있으며, 초급 프로젝트를 통해 개발 및 프로젝트에 대한 경험을 키워나가고 있습니다.  
        장기적으로는 인공지능에 대한 전문성을 위해 빅데이터분석기사의 취득이나 마이크로소프트나 구글 등의 국제 기관에서 주관하는 자격증을 취득하는 것이 목표입니다.  
        그리고 이것을 기반으로 인공지능에 대한 연구나 개발을 전문적으로 수행하는 기관에 소속되어 새로운 패러다임을 이끄는 한 축이 되고 싶습니다.

        {{< icon name="download" pack="fas" >}} {{< staticref "uploads/이력서.pdf" "newtab" >}}다운로드{{< /staticref >}} 내 이력서를 PDF로 받기


  - block: features
    id: features
    content:
      title: My Interests
      text: 아래는 저의 관심사에 대한 소개입니다!
      items:
        - name: 인공지능(AI)
          icon: cogs
          icon_pack: fas
          description: 데이터마이닝 및 머신러닝 AI 기술 적용.
        - name: 포렌식(Forensic)
          icon: fingerprint
          icon_pack: fas
          description: 디지털포렌식 관련 분야 응용.
        - name: 수학(Medical Math)
          icon: square-root-alt
          icon_pack: fas
          description: 데이터분류에 대한 통계 분석 모델링 관련 연구 수행.
        - name: Security
          icon: comment-dots
          icon_pack: fas
          description: 정보보안 관련 연구 및 학습.
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description: 시큐어코딩 및 리버싱 관련 어셈블리어 공부.
        - name: 글쓰기(Writing)
          icon: pen
          icon_pack: fas
          description: 글쓰기 관련 활동.
    design:
      columns: '1' # 그리드 뷰를 위해 2 또는 3으로 변경 가능
      css_class: justify-text
      background:
        color: '#0f1fab'
