---
layout: post
title: "[Jekyll] pages build and deployment error"
date: 2019-03-23 21:03:36 +0900
categories: Github Jekyll
---

지킬 테마를 사용해 깃허브 블로그를 세팅하는 과정 중 `pages build and deployment` 에러를 겪었다.

<img width="1534" alt="스크린샷 2022-07-29 오후 5 46 45" src="https://user-images.githubusercontent.com/80310308/181724540-1ca594d8-8fd7-46e9-9db0-e7575ca006ec.png">

<img width="1534" alt="스크린샷 2022-07-29 오후 5 47 03" src="https://user-images.githubusercontent.com/80310308/181724697-436301f4-53eb-41f8-965a-bfa4af45c628.png">

해결 방법은 `_config.yml`에 있다.

<img width="260" alt="스크린샷 2022-07-29 오후 5 55 31" src="https://user-images.githubusercontent.com/80310308/181725077-c01a4e20-0aab-4abd-9ad2-c588365fe846.png">

```
theme:
remote_theme:
```

이 부분을 주석처리하거나, 삭제하면 된다.

<img width="1534" alt="스크린샷 2022-07-29 오후 5 59 50" src="https://user-images.githubusercontent.com/80310308/181725566-2f1ad570-0651-4f13-b026-0019a8d7c30a.png">

다음과 같이 해결되었다.
