---
title: 'Education, Awards & Skills' # 페이지 제목에 Education을 추가했습니다.
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-education  # 📝 Education 섹션을 추가합니다.
    content:
      username: admin
      title: Education
    design:
      # Hugo date format (날짜 형식을 유지합니다)
      date_format: 'January 2006' 
  - block: resume-awards  # 🏆 Awards 섹션 (Awards & Recognition)
    content:
      title: Awards & Recognition
      username: admin
  - block: resume-skills  # 🛠️ Skills 섹션
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-languages # 🗣️ Languages 섹션
    content:
      title: Languages
      username: admin
---