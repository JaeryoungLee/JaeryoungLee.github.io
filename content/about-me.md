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
          Two-year Full-tuition Scholarship<br><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
  <path stroke-linecap="round" stroke-linejoin="round" d="M12 18v-5.25m0 0a6.01 6.01 0 0 0 1.5-.189m-1.5.189a6.01 6.01 0 0 1-1.5-.189m3.75 7.478a12.06 12.06 0 0 1-4.5 0m3.75 2.383a14.406 14.406 0 0 1-3 0M14.25 18v-.192c0-.983.658-1.823 1.508-2.316a7.5 7.5 0 1 0-7.517 0c.85.493 1.509 1.333 1.509 2.316V18" />
</svg>

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
