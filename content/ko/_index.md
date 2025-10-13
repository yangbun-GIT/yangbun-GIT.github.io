---
# Leave the homepage title empty to use the site title
title:

type: landing

design:
  spacing: "7rem"

sections:
  - block: features
    content:
      title: ""
      text: |
        <div style="text-align:center; font-size:1.2rem; line-height:1.35;">
          <img src="avatar.jpg" alt="프로필 이미지" style="width:170px; height:170px; border-radius:50%; object-fit:cover; filter:brightness(0.95); margin-bottom:16px; display:block; margin-left:auto; margin-right:auto; box-shadow:0 0 15px rgba(0,0,0,0.2);" />

          <div style="font-weight:bold; font-size:1.6rem; margin-bottom:13px;">윤영준</div>
          <div style="margin-bottom:10px;">
            전북대학교 공과대학 IT정보공학과(現-컴퓨터인공지능학부)
          </div>
          <div style="margin-bottom:15px;">
            <a href="https://csai.jbnu.ac.kr/csai/index.do" target="_blank" style="margin:0 10px; font-weight:bold;">전북대학교 컴퓨터인공지능학부</a>
          </div>

          <div style="margin-bottom:13px;">
            <a href="mailto:yang_bun@jbnu.ac.kr" style="margin:0 8px; font-size:1.3em;"><i class="fas fa-envelope"></i></a>
            <a href="https://github.com/yangbun-GIT" style="margin:0 8px; font-size:1.3em;"><i class="fab fa-github"></i></a>
            <a href="https://kr.linkedin.com/" style="margin:0 8px; font-size:1.3em;"><i class="fab fa-linkedin"></i></a>
            <a href="https://www.instagram.com/0_jun_03/" style="margin:0 8px; font-size:1.3em;"><i class="fab fa-instagram"></i></a>
            <a href="https://stackoverflow.com/questions" style="margin:0 8px; font-size:1.3em;"><i class="fab fa-stack-overflow"></i></a>
            <a href="https://x.com/" style="margin:0 8px; font-size:1.3em;"><i class="fab fa-x-twitter"></i></a>
            <a href="https://www.facebook.com/" style="margin:0 8px; font-size:1.3em;"><i class="fab fa-facebook"></i></a>
          </div>

          <div style="margin-bottom:8px;">
            전북대학교 IT정보공학과(現-컴퓨터인공지능학부)에 재학중인 <b>윤영준</b>입니다.<br>
            저는 현재 3학년 2학기 과정을 수료중입니다.<br>
            이곳에서  '<a href='/ko/about/'>소개</a>'  저에 대한 정보를 확인할 수 있습니다.
          </div>
        </div>
        
  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%; font-weight:bold;">AI</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                현실을 혁신하는 지능형 패턴 탐색
              </div>
            </div>
          align: center
          background:
            image:
              filename: shawn-day-ii6BOPjAtVY-unsplash.jpg
              filters:
               brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%; font-weight:bold;">알고리즘</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                데이터 흐름을 최적화하는 혁신적 알고리즘
              </div>
            </div>
          align: center
          background:
            image:
              filename: Algorithm.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%; font-weight:bold;">개발</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                최신 트렌드를 반영한 유연한 소프트웨어 제작
              </div>
            </div>
          align: center
          background:
            image:
              filename: annie-spratt-QckxruozjRg-unsplash.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'

        - title: <span style="font-size:70%; font-weight:bold;">네트워크</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                분산 환경에서 안정적인 데이터 흐름을 보장
              </div>
            </div>
          align: center
          background:
            image:
              filename: nasa-Q1p7bh3SHj8-unsplash.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
            
        - title: <span style="font-size:70%; font-weight:bold;">보안</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                지능형 위협 분석으로 사이버 위험을 사전에 차단
              </div>
            </div>
          align: center
          background:
            image:
              filename: Security.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
            
    design:
      slide_height: '475px'
      slide_width: '100px'
      is_fullscreen: false
      loop: true
      interval: 4000

  - block: collection
    content:
      id: section-1
      title: 언어
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - language
    design:
      view: custom_card
      columns: '1'
      css_class: justify-text
      
  - block: collection
    content:
      id: section-2
      title: 학습
      subtitle: ''
      text: ''
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - class
    design:
      view: custom_compact  
      columns: '1'
      css_class: justify-text
      
  - block: collection
    content:
      id: section-3
      title: 프로젝트
      subtitle: ''
      text: ''
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - project
    design:
      view: showcase
      columns: '1'
      css_class: justify-text

---
