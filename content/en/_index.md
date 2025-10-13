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
          <img src="avatar.jpg" alt="Profile Image" style="width:170px; height:170px; border-radius:50%; object-fit:cover; filter:brightness(0.95); margin-bottom:16px; display:block; margin-left:auto; margin-right:auto; box-shadow:0 0 15px rgba(0,0,0,0.2);" />

          <div style="font-weight:bold; font-size:1.6rem; margin-bottom:13px;">Yun Yeong-jun</div>
          <div style="margin-bottom:10px;">
            Department of IT and Information Engineering, College of Engineering, Jeonbuk National University (Current-Department of Computer Science and Artificial Intelligence)
          </div>
          <div style="margin-bottom:15px;">
            <a href="https://csai.jbnu.ac.kr/csai/index.do" target="_blank" style="margin:0 10px; font-weight:bold;">Department of Computer Science and Artificial Intelligence, Jeonbuk National University</a>
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
            I am <b>Yun Yeong-jun</b>, a student in the Department of IT and Information Engineering (now the Department of Computer Science and Artificial Intelligence) at Jeonbuk National University.<br>
            I am currently completing my second semester of my third year.<br>
            You can find information about me here: ‘<a href=’/ko/about/‘>About Me</a>’.
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
                Intelligent Pattern Discovery That Innovates Reality
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

        - title: <span style="font-size:70%; font-weight:bold;">Algorithm</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                Innovative algorithm for optimizing data flow
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

        - title: <span style="font-size:70%; font-weight:bold;">Development</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                Flexible software development reflecting the latest trends
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

        - title: <span style="font-size:70%; font-weight:bold;">Network</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                Ensuring stable data flow in a distributed environment
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
            
        - title: <span style="font-size:70%; font-weight:bold;">Security</span>
          content: |
            <div style="position: relative; font-size: 75%;">
              <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0, 0, 0, 0.7); z-index: 1;"></div>
              <div style="position: relative; z-index: 2; color: white;">
                Preemptively block cyber risks through intelligent threat analysis
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
      title: Language
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
      title: Learning
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
      title: Project
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
