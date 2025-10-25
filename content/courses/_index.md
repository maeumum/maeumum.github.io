---
# 이 페이지 자체의 제목과 요약을 비워서, 불필요한 카드가 표시되지 않도록 합니다.
title: ''
summary: ''
type: landing

# 하위 모든 페이지(학기 및 과목)를 Docs 타입으로 설정하여 사이드바와 경로 표시를 활성화합니다.
cascade:
  - target:
      path: '{/courses/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: semesters
    content:
      title: 학기별 학습 기록 (Academic Semesters)
      filters:
        # courses 폴더 바로 아래의 모든 섹션(2024-1, 2024-2 등)을 불러옵니다.
        folders:
          - courses 
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---