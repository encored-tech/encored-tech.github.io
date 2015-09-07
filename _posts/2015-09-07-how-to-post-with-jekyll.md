---
layout: post
title: "(포스트 예제) 지킬 블로그에 포스트하는 방법"
date: 2015-09-07 13:46
---

## 포스트 추가

포스트를 추가하려면

* GitHub 계정으로 로그인합니다.
* [블로그 소스코드 페이지](https://github.com/encored-tech/encored-tech.github.io)에 접속합니다.
* `_posts` 디렉토리로 이동합니다.
* 탐색창 위쪽의 경로 표시줄에 나온 `encored-tech.github.io` / `_posts` / `+` 에서 `+` 링크를 클릭합니다.
* 파일명을 다음과 같이 입력합니다: 년-월-일-제목.md (예: `2015-09-07-a-new-article-title.md`) 이 때, 빈 칸은 쓰지 마시고 `-`로 대신해야 합니다. 제목은 한글로 써도 무방합니다.
* 파일 내용은 다음과 같은 형식으로 입력합니다.

제일 윗 줄에는 아래 내용이 삽입되어야 합니다.

    ---
    layout: post
    title: "포스트 제목"
    date: 년-월-일 시:분
    ---

그 아래 줄부터는 [마크다운](http://scriptogr.am/myevan/post/markdown-syntax-guide-for-scriptogram) 형식에 맞게 작성합니다.

### 마크다운 포맷 관련 읽을거리

* [마크다운 문법 가이드](http://scriptogr.am/myevan/post/markdown-syntax-guide-for-scriptogram)
* [마크다운으로 글을 써보자](http://blog.kalkin7.com/2014/02/10/lets-write-using-markdown/)

### 이 포스트를 삭제하려면

이 포스트는 GitHub 페이지에서 `_posts/2015-09-07-how-to-post-with-jekyll.md` 파일을 삭제하시면 삭제됩니다.

