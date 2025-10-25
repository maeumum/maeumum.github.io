---
title: Courses
summary: Semester study records
type: landing

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
      title: Academic Semesters
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