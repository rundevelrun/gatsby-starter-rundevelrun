---
emoji: "✍️"
title: "블로그 포스트 작성법"
date: 2025-01-18 13:55:01
update: 2025-01-18 13:55:01
tags:
  - rundevelrun
  - writing
series: "Gatsby 블로그 시작하기"
---

이 스타터는 Gatsby의 파일 기반 라우팅을 활용하여, `content/blog/` 폴더에 Markdown 파일을 추가하면 자동으로 포스트가 생성됩니다.

## 📁 기본 구조

```
contents/
  posts/
    hello-world/
      index.md
```

## 📝 Frontmatter

```md
---
emoji: "🚀"
title: "어떻게 시작할까요?"
date: 2025-01-18 13:55:00
update: 2025-01-18 13:55:00
tags:
  - rundevelrun
  - howto
series: "Gatsby 블로그 시작하기"
---
```

## ✍️ 콘텐츠 작성

Markdown 문법을 사용하여 본문을 작성하세요. 코드 블록, 이미지, 표 등도 모두 지원합니다.

예시:

````md
## 서론

이 블로그는 Gatsby와 Markdown을 기반으로 만들어졌습니다.

```js
console.log("Hello Gatsby!");
```
````