---
title: "[Blog]블로그 설정 (1)"
excerpt: "_config에서 몇가지 수정하여 블로그를 갖추어 주자."
data: 2022-01-02
last_modified_at: 2022-01-07
categories: Blog
tag: Blog
toc: true
---

# minstake 블로그 깃헙 가이드

### 출처:

-   [minstake Blog 가이드](https://mmistakes.github.io/minimal-mistakes/docs/configuration/)
-   [유툽 테디노트](https://www.youtube.com/watch?v=0TeHUqSAb6Q&list=PLIMb_GuNnFwfQBZQwD-vCZENL5YLDZekr&index=3)
-   []()

<br><br/>

---

## Skin

### - config.yml

기본값으로는 default 되어있지만.

-   **air**
-   **aqua**
-   **contrast**
-   **dark**
-   **dirt**
-   **neon**
-   **mint**
-   **plum**
-   **sunrise**

가이드에서 해당 테마를 선택하고 출발하자.

이후에 내가 원하는대로 수정하면 된다.

### _수정사항_

> 임의로 수정하는 과정 추가.

<br><br/>

---

## 프로필

-   locale: "ko-KR"
    -   블로그의 주요 언어입니다. 한국어 ko-KR로 설정
        <br></br>
-   title: "Jeong_BreadBasket"
    -   사이트 탭
        <br></br>
-   title_separator: "|"
    -   브라우저 탭에서 블로그 | 게시물명으로 구분지어줍니다.
        <br></br>
-   subtitle: "보고 배운 것을 저장하는 곡창"
    -   화면 title 하단에 있는 소제목
        <br></br>
-   name: "Jeong Min Gyun"
    <br></br>
-   description: "곡창"
    -   설명란
        <br></br>
-   url: "https://jeongsam3659.github.io/"
    -   Github Repo url입니다.

### _수정사항_

> 이미지를 추가하여 어디에 해당되는지 이미지를 넣기

<br><br/>

---

## 경로 표시

**BreadCrumb navigation**
<br></br>
config.yml에서 breadcrumbs를 true 설정.

-   게시물을 들어가면 상단에 경로를 보여줍니다.

> ex\_ HOME / 게시물명.

<br></br>

---

## 작성 일자

config.yml에서 defaults부근(맨 밑)  
\_posts에서 values칸에 **show_date: true**를 추가하여 작성일자 표기하는 방법.  
<br></br>
default 형태로는 월 일, 년

> December 29, 2021

<br></br>

---

## 댓글

#### Comments

1. Disqus 댓글을 사용.

    - 구글계정을 가입후 프로필 \> setting \> add Disqus to Site
      <br></br>
    - 맨 밑의 Get Started 후, 두번째 i want to install disqus on my site. 클릭
      <br></br>
    - 이름과 비즈니스를 설정하고 나머진 고대로 둔뒤
      <br></br>
    - 무료 버젼을 사용하기 위해 Basic을 구독, jekyll 선택.
      <br></br>
    - configure에서  
       Website URL: https://깃헙주소(ex\_ https://jeongsam3659.github.io/)
      Next - complete setup. 등록완료
      <br></br>

2. config.yml
    - defaults부근에 comments: true로 바꿔주고
      <br></br>
    - 윗쪽 Comments에서
      provider: "disqus"로 수정
      <br></br>
    - disqus사이트에서 상단 admin 클릭하면  
      **check out what's been happening on your 1 sites.** 커맨드에  
      **Select a specific site.** 클릭하여  
      팝업창 밑에 자신의 깃블로그 선택하면  
      **check out what's been happening on jeongGitBlog.**  
      라는 문구가 나오는데 여기서 jeongGitBlog \<\< 이게 숏네임 이다.
