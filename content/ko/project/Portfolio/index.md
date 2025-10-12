---
title: 포트폴리오 페이지 제작
date: 2025-10-13
---

초급프로젝트
  - HTML/CSS/Javascript를 사용하지 않고, Hugo builder Demo를 사용하여 개인 포트폴리오 홈페이지를 제작

<!--more-->

- 소셜 미디어 연동
  - content/authors/admin/_index.md에서 social: 섹션을 찾아 연결하고 싶은 소셜 미디어 정보를 추가
- PDF 파일 다운로드
  - 프로젝트의 static/uploads에 다운로드할 PDF 파일(resume.pdf)을 추가
  - 다운로드 링크를 추가하고 싶은 페이지(.md)에 마크다운 링크 형식으로 링크를 추가
- baseURL 변경
  - config/_default/hugo.yaml에서 baseURL 값을 GitHub Pages 주소로 변경
