---
title: ''
summary: ''
type: landing

# 이 페이지 자체를 collection에서 제외
_build:
  render: always
  list: false  # 리스트에서 제외

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
        folders:
          - courses 
        kinds:
          - section
        # 자기 자신(_index.md)을 제외
        exclude:
          - '**/courses/_index.md'
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---