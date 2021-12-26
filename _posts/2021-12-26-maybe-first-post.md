---
title: "블로그 첫 포스팅"
excerpt: "md 파일에 마크다운 문법으로 작성하여 Github에 업로드 하기"

catergories:
 - Blog
 tags:
 - [Blog, Github]

toc: true
toc_sticky: true

data: 2021-12-26
last_modified_at: 2021-12-26
---

### 머릿말(Front-Matter)

- title: 포스트의 제목을 큰 따옴표로 적는다.
- excerpt: 포스트 목록에서 보여지는 블로그 소개 글.
- categories: 포스트의 카테고리
- tags: 태그
- tags 와 categories의 차이점은 카테고리는 sub url이 붙는 페이지가 있지만 태그는 없다.
  좀더 세부적으로 할시 [태그1 , 태그2] 구분지어 지정.

- toc: Table of Contents 포스트의 헤더들만 보여주는 목차를 사용할 것인지의 여부.
  true로 할 경우 포스트의 목차가 보이게 된다.

- toc_sticky: true로 해주면 목차가 스크롤을 따라 움직인다. toc_icon, toc_label로 설정할 수 있다.

- date: 글을 처음 작성한 날짜. yyyy-mm-dd 형식
- last_modified_at: 이 글을 수정한 날짜.

layout, permalink, published, author_profile 등등의 변수가 있다고한다.
