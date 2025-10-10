---
# An instance of the About widget.
# Documentation: https://docs.hugoblox.com/page-builder/
# widget: about
widget: widget_page

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: ''

# Choose the user profile to display
# This should be the username (folder name) of a profile in your `content/authors/` folder.
# See https://docs.hugoblox.com/get-started/#introduce-yourself
# author: admin

# Page sections
sections:
  - block: about.avatar
    content:
      username: admin
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
      css_class: justify-text
      background:
        color: '#0f1fab'
---
