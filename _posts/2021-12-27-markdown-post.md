---
title: "[Blog]마크다운MarkDown 언어"
excerpt: "md파일에 언어를 사용해서 블로그를 이어가자"
data: 2021-12-27
last_modified_at: 2021-12-27
---

<!-- Heading -->

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

- h1 ~ h6까지 표현 가능한 (# 갯수)로 표현할 수 있다.

> 일반적 텍스트 작성시에는 아무 기호없이 사용하면 된다.

<!-- Line -->

---

## Line

> 구분선은 \_을 세번 ( \_\_\_ ) 사용하면 구분선이 나타난다.

---

<!-- Text Attributes -->
<!-- bold -->

## 텍스트 속성

### bold , italic , 취소선

This is the **bold** text and this is the _italic_ text and let's do ~~strikethrough~~.

이게 **굵은 글씨**고 이게 *이탤릭 글씨*고 ~~취소선~~을 해봅시다.

> bold \*\*글자\*\* ,
> italic \*글자\* ,
> 취소선 \~~글자\~~

---

<!-- Quote -->

## Quote 인용

> \' \> \' 를 사용하여 구분지는 인용문?을 나타나게 할 수 있다.

---

<!-- Bullet List -->

## Bullet List 순서없는 리스트

라면:

- 신라면
- 안성탕면
- 무파마

그 밖:

- 짜파게티
- 멸치 칼국수

> \* 이나 \- 으로 순서없는 리스트를 생성할 수 있다.

웹

- 프론트
  - html/css
  - Js
    - React
    - anguler
- 백엔드

  - java

    - Spring

  - Python

등으로 하위 부분을 표현할때 탭(TAB) + \* \- 사용하면 된다.

---

<!-- Numbered list -->

## Numbered list 순서있는 리스트

Numbers:

1. 첫째
2. 둘째
3. 셋째

간단하게 숫자로 표현할 수 있다.

---

<!-- Link -->

## Link 링크

Click [네이버](https://www.naver.com/)

> \[ 문자 \] \( 웹 주소 \) 를 기입하면 '네이버' 클릭시 네이버 페이지로 이동합니다.

---

<!-- image -->

## image 이미지

![image 에 대한 설명](https://github.com/jeongsam3659/jeongsam3659.github.io/tree/main/assets/img/free_img.jpg)

> \! \[image 설명\]\( 이미지 주소 \)

---

<!-- Table -->

## Table

| Header | Description |
| ------ | ----------- |
| Cell1  | Cell2       |
| Cell1  | Cell2       |
| Cell1  | Cell2       |
| Cell1  | Cell2       |

#### \| 헤더 \| 헤더2 \|

#### \| -- | -- |

#### \|cell1\| \|cell2\|

로 표현할 수 있으며

#### \| --: |

우측정렬

#### \| :-- |

좌측정렬

#### \| :--: |

가운데정렬

---

<!-- Code -->

## Code

콘솔 로그를 표현하고 싶을시
`console.log('Hello!')`

#### \` 백틱 키를 넣어표현할 수 있으며

#### \`\`\` \`\`\` 으로 코드 블록을 나타내고

```js
console.log("Hello!");
```

상단 \`\`\` 옆에 js, java, ts 등등 해당 언어를 기입하면 가독성이 높아진다.

---

# 참고

- [드림코딩 by엘리](https://www.youtube.com/watch?v=kMEb_BzyUqk&t=3s) 마크다운
- 구글신
