---
title: "홈페이지"
date: 2022-10-24
type: landing

sections:
  - block: collection
    id: teaching
    content:
      title: Featured Teaching
      # 필터를 사용하여 표시할 폴더 지정
      filters:
        folders:
          - teaching  # content/teaching/에 있는 파일들을 표시
    design:
      view: card  # 커스텀된 collection.html이 카드 형식으로 표시되도록 설정
      columns: 2  # 한 행에 표시할 카드의 수를 조정
---
