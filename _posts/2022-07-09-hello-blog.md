---
title:  "블로그 개설"
date:   2022-07-09 20:15:00 +0900
categories: Diary
badges:
 - type: warning
   tag: Diary
---


회사에서 git을 쓰고 있긴 하지만 솔직히 git에 대한 이해도가 높지 않다. 그냥 내 로컬에서의 수정사항을 branch에 push 하고, master에 merge 하는 정도만 이해하고 사용 중이다. 잘 모르니까 git 사용 중에 문제가 생겼을 때도 적극적인 조치가 쉽지 않다. 그러다 보니 이런저런 상황을 경험해볼 기회도 별로 없다. 그래서 이번에는 이왕 블로그를 개설하는거 한 번 github에서 개설해보자고 마음먹었다. 인터넷에 블로그 개설을 위한 가이드들이 아주 많아서 걱정했던 것 보다는 쉽게 진행할 수 있었다. 오늘 이걸 한 번 해봤다고 해서 git에 대한 이해도가 올라가진 않았지만 앞으로 꾸준히 사용해보다 보면 여러가지 배우게 되지 않을까 기대해본다.

## Docsy Jekyll Theme

일단은 디자인이 마음에 들어서 선택한 테마인데 여러가지 수정하고 싶은 부분이 많다.
* 오른쪽 메뉴 구성 변경
* 왼쪽 첫 번째 Documentation 메뉴 링크가 Archive를 바라보지 않게 하기
* 파비콘 이미지 변경하기

그런데 새로운 문서는 posts 경로에 쓰면 된다고 했는데 posts에 작성한건 검색으로 접근할 수 있는 것 같고 dosc에 작성한 것들이 Documentation 밑에 노출되는 것 같다. 내 용도에 맞지 않는 테마였던 걸까? 아님 docs 밑에 적절한 폴더를 나눠서 문서들을 작성하는 쪽으로 사용해버릴까?

[Jekyll 가이드][Jekyll 가이드]에 의하면 일단 posts에 쓰는 것 같긴 한데 아직 잘 모르겠다.

post 주소에 baseline url이 포함되지 않아서 그랬던 것 같다. base url을 넣었다 뺐다 페이지가 정상적으로 보였다 깨졌다 난리를 한바탕 치고 이제 페이지는 정상적으로 보이게 되었다.

[Jekyll 가이드]: https://jekyllrb.com/docs/posts/

로컬에서 블로그 변경사항 확인하기 

```bash
jekyll serve
# or
bundle exec jekyll serve
```