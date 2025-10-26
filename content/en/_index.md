---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
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

  - block: gallery
    content:
      title: ''
      subtitle: ''
      items:
        - image: media/slide1.jpg
          caption: 'Exploring AI frontiers'
        - image: media/slide2.jpg
          caption: 'Collaborative research'
        - image: media/slide3.jpg
          caption: 'Data-driven innovation'
      slider: true
      autoplay: true
      interval: 4000
    design:
      columns: '1'
      spacing:
        padding: ['2rem', '2rem', '2rem', '2rem']
---
