---
title: "[Blog]블로그시 업데이트 실시간 확인"
excerpt: "ruby를 활용한 블로그 로컬 서버로 페이지 확인하는 법"
data: 2021-12-29
last_modified_at: 2021-12-29
categories: Blog
tag: GithubBlog
---

# 1.

github 블로그시 수정 및 추가사항을 추가하여도

사이트에 추가해도 어떻게 반영되였는지 볼려면

push하고도 좀 있다가 기다려야 적용된다.
<br><br/>

---

## mmistakes의 블로그 사용시

해당 테마블로그에 [가이드](https://mmistakes.github.io/minimal-mistakes/docs/installation/)에 보면 **install dependencies** 칸에 [official documentation](https://jekyllrb.com/docs/)을 클릭하면 필수 설치 목록을 확인 및 가이드를 볼 수 있다.<br><br/>

---

## Ruby

### [Ruby](https://www.ruby-lang.org/en/downloads/)

본인의 OS (window/macOS)에 따라 들어간뒤 Download에 들어가 최신With DEVKIT(데브킷)을 설치.
<br><br/>

cmd-ruby창이 등장하는데 3번 + enter로 설치.
<br><br/>

## Ruby cmd

1. cmd 실행.
2. gem install jekyll.
3. gem install bundler.

순서대로 cmd창에 입력하여 설치.
<br><br/>

## Powershell

- 프로젝트 폴더 선택 + shift + 우클릭시
- powershell 창 실행.

cd 프로젝트폴더 로 들어가서.

- **bundle install** 설치. 완료 후
- bundle exec jekyll serve.

> 만약 ERROR **'cannot load such file -- webrick'** 시
> bundle add webrick로 설치.

---

## 로컬 서버

- Server address: http://127.0.0.1:4000 로 서버가 열렸다는 것을 알 수 있다.

> 인터넷 주소창에 http://127.0.0.1:4000/ 치면 블로그가 나오는걸 볼 수 있다. (로컬 서버)

## <br><br/>

---

출처: [유튭 테디노트](https://www.youtube.com/watch?v=0TeHUqSAb6Q&list=PLIMb_GuNnFwfQBZQwD-vCZENL5YLDZekr&index=3)
