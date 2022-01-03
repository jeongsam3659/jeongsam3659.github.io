---
title: "[Blog]코드 예제 출력확인"
excerpt: "작성한 코드가 출력되는지 확인 페이지."
data: 2022-01-02
last_modified_at: 2022-01-02
categories: Blog
tag: java
toc: true
---

## java 출력 확인

<br><br/>

```java
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int a, b;
        a = sc.nextInt();
        b = sc.nextInt();
        System.out.println(a+b);
    }
}

```
