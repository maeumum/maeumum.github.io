---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  # 이미지 슬라이더 추가 (맨 위에 배치)
  - block: slider
    content:
      slides:
        - title: Welcome to My Portfolio
          content: 전북대학교 컴퓨터인공지능학부 학생입니다
          align: center
          background:
            image:
              filename: slider-1.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#666'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Learn More
            url: /#about
            
        - title: My Projects
          content: 다양한 프로젝트를 진행하고 있습니다
          align: left
          background:
            image:
              filename: slider-2.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
          link:
            icon: code
            icon_pack: fas
            text: View Projects
            url: /projects/
            
        - title: Research & Development
          content: AI와 소프트웨어 개발에 관심이 있습니다
          align: right
          background:
            image:
              filename: slider-3.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#333'
          link:
            icon: flask
            icon_pack: fas
            text: See Research
            url: /#papers
    design:
      # 슬라이더 높이 조절
      slide_height: '500px'
      # 자동 재생 활성화
      is_fullscreen: false
      # 슬라이드 전환 효과
      loop: true
      # 자동 전환 간격 (밀리초)
      interval: 5000

  - block: resume-biography-3
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

        Please reach out to collaborate 😃
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---