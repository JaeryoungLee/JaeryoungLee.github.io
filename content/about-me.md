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

  - block: markdown
    content:
      title: 'Scholarships'
      text: |-
      **Graduate**<br>
        Korean Government Scholarship for Overseas PhD Study ($80,000)<br>
        &nbsp;&nbsp;&nbsp;&nbsp;<small>_Korea National Institute for International Education_ | _2025 – 2027_ (expected)</small><br>
        Two-year Full-tuition Scholarship<br>
        &nbsp;&nbsp;&nbsp;&nbsp;<small>_KAIST & Ministry of Science and ICT_ | _2023 – 2025_</small>

      **Undergraduate**<br>
        Kim Young-Han (KYH) Global Leader Scholarship<br>
        &nbsp;&nbsp;&nbsp;&nbsp;<small>_KAIST_ | _2021_</small><br>
        Academic Excellence Scholarship<br>
        &nbsp;&nbsp;&nbsp;&nbsp;<small>_KAIST_ | _Two semesters in 2021_</small><br>
        Two-year Boeing Scholarship<br>
        &nbsp;&nbsp;&nbsp;&nbsp;<small>_KAIsIST & Ministry of Science and ICT_ | _2018-2023_</small><br>  
    design:
      columns: '1'


  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: admin

  - block: resume-languages
    content:
      title: Languages
      username: admin

  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
---
