---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
    title: ""
    text: |
      <img src="/ko/authors/admin/avatar.jpg" alt="프로필 이미지" style="width:120px; border-radius:50%; margin-bottom:10px;" />

      <div style="font-size:1.6em; font-weight:bold; margin-bottom:4px;">윤영준</div>
      <div style="font-size:1em; margin-bottom:6px;">전북대학교 공과대학 IT정보공학과(現-컴퓨터인공지능학부)</div>
      <div style="margin-bottom:6px;">
        <a href="https://csai.jbnu.ac.kr/csai/index.do" target="_blank">전북대학교 컴퓨터인공지능학부</a>
      </div>

      <a href="mailto:yang_bun@jbnu.ac.kr"><i class="fas fa-envelope"></i></a>
      <a href="https://github.com/yangbun-GIT"><i class="fab fa-github"></i></a>
      <a href="https://x.com/"><i class="fab fa-x-twitter"></i></a>
      <a href="https://kr.linkedin.com/"><i class="fab fa-linkedin"></i></a>
      <a href="https://www.instagram.com/0_jun_03/"><i class="fab fa-instagram"></i></a>

      전북대학교 IT정보공학과(現-컴퓨터인공지능학부)에 재학중인 **윤영준**입니다.  
      저는 현재 3학년 2학기 과정을 수료중입니다.  
      이곳에서   "<a href='/ko/about/'>소개</a>"  저에 대한 정보를 확인할 수 있습니다.

  - block: slider
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
            position: center
            color: '#1dc6f5'

        - title: <span style="font-size:70%">AI</span>
          content: <span style="font-size:70%">비전/데이터마이닝 분야에 적용 가능한 AI 기술 개발</span>
          align: center
          background:
            image:
              filename: ai.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#d346e3'

        - title: <span style="font-size:70%">디지털포렌식</span>
          content: <span style="font-size:70%">사이버수사대 디지털포렌식 중요도 증가</span>
          align: center
          background:
            image:
              filename: for.jpg
              filters:
                brightness: 0.3
            position: center
            color: '#7986ba'

        - title: <span style="font-size:70%">Math</span>
          content: <span style="font-size:70%">데이터마이닝 및 AI 활용 수학 연구</span>
          align: center
          background:
            image:
              filename: math.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#bd4646'
    design:
      slide_height: '600px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
      interval: 3000
---
