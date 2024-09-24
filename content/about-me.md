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
    content:
      title: Scholarships
      text: |-
        **Graduate**<br>
        - Korean Government Scholarship for Overseas PhD Study ($80,000)<br>
          <div style="text-align: right"><small>_2025 – 2027 (expected)_</small><br></div>
        - Two-year Full-tuition Scholarship<br>
           <div style="text-align: right"><small>_KAIST & Ministry of Science and ICT, 2023 – 2025_</small></div>

        **Undergraduate**<br>
        - Kim Young-Han (KYH) Global Leader Scholarship<br>
           <div style="text-align: right"><small>_KAIST, 2021_</small><br>
        - Academic Excellence Scholarship</div><br>
           <div style="text-align: right"><small>_KAIST, Two semesters in 2021_</small</div>><br>
        - Two-year Boeing Scholarship<br>
           <div style="text-align: right"><small>_KAIST & Boeing Korea, 2020-2021_</small></div><br>
        - Five-year Full-tuition Scholarship<br>
           <div style="text-align: right"><small>_KAIST & Ministry of Science and ICT, 2018-2023_</small></div><br>
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
---
