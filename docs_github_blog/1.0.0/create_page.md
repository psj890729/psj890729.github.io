---
layout: page
title: 페이지 만들기
redirect_from:
  - /docs_github_blog/create_page/
  - /docs_github_blog/create_page/
---


새로운 페이지나 새로운 포스트를 작성할때 아래와 같이 작성해야 한다.

```
---
layout: page
title: Github Blog
menu: true
order: 5
---
```

#### layout
- `layout: page` 페이지로 만들기 
- `layout: post` 포스트로 작성하기 

#### title
- 페이지의 제목

#### menu
- `true` 이면 왼쪽에 메뉴가 새롭게 생성됨
- `false` 이면 왼쪽에 메뉴가 나오지 않음
- `# menu` 이렇게 해도 주석처리가 되어 메뉴가 나오지 않음

### order
- 좌측 메뉴의 위치
- 1이면 맨위에 위치한다.
