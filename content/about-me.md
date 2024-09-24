---
title: 'About Me'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false


  - block: markdown
    id: scholarships
    content:
      title: Scholarships
      text: |
      **Graduate**
      Korean Government Scholarship for Overseas PhD Study ($80,000)
        <small>2025 – 2027 (expected)</small>
      Two-year Full-tuition Scholarship 
        <small>KAIST & Ministry of Science and ICT, 2023 – 2025</small>

      **Undergraduate**
      Kim Young-Han (KYH) Global Leader Scholarship
        <small>KAIST, 2021</small>
      Academic Excellence Scholarship
        <small>KAIST, Two semesters in 2021</small>
      Two-year Boeing Scholarship
        <small>KAIST & Boeing Korea, 2020-2021</small>
      Five-year Full-tuition Scholarship
        <small>KAIST & Ministry of Science and ICT, 2018-2023</small>


  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: admin

  - block: resume-languages
    content:
      title: Languages
      username: admin
---
