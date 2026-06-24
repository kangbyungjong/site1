# 이형철법무사사무소 정보형 블로그

Netlify 배포용 Eleventy 정적 블로그입니다.

## Netlify 설정

- Build command: `npm run build`
- Publish directory: `_site`
- Node version: `22`

## 글 추가 방법

새 글은 `src/posts/` 폴더에 Markdown 파일로 추가합니다.

```md
---
title: "글 제목"
description: "검색 결과에 보일 설명"
date: 2026-06-24
permalink: /blog/example-post/
tags: posts
---

본문을 작성합니다.
```

도메인을 연결한 뒤 `src/_data/site.json`의 `url` 값을 실제 도메인으로 바꾸세요.
