---
title: Courses
summary: My courses
type: landing

cascade:
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: courses
    content:
      title: My Courses # 제목을 명확히 변경
      filters:
        folders: # 이 줄을 추가하여 courses 폴더 바로 아래의 모든 폴더를 대상으로 지정
          - courses 
        kinds:
          - section # Docs 섹션 페이지 (즉, 학기별 _index.md)를 불러옴
        # tag: Course # 이 필터를 제거합니다.
    design:
      view: article-grid # 카드 목록으로 표시
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---
