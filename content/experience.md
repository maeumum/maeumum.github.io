---
title: 'Awards & Skills' # 페이지 제목을 '수상 및 역량'으로 변경
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-awards  # 🏆 Awards 섹션을 맨 위로 이동시켜 강조합니다.
    content:
      title: Awards & Recognition
      username: admin
  - block: resume-skills  # 🛠️ Skills 섹션을 다음으로 배치
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-languages # 🗣️ Languages 섹션 유지
    content:
      title: Languages
      username: admin
  # --- 기존의 'resume-experience' 블록은 완전히 제거되었습니다. ---
---