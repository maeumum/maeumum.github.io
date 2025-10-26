---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block : gallery
    id : image-slider
    content:
      title: ''
      subtitle: ''
      items:
        - image: slide1.jpg
          caption: 'Exploring AI frontiers'
        - image: slide2.jpg
          caption: 'Collaborative research'
        - image: slide3.jpg
          caption: 'Data-driven innovation'
      # 슬라이더(캐러셀) 활성화
      slider: true
      autoplay: true
      interval: 4000 # 밀리초 단위 (4초)
    design:
      columns: '1'
      spacing: '2rem'
---
