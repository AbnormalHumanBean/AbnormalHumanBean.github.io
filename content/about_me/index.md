---
title: "About Me"  # Add a page title.
date: "2024-01-01"  # Add today's date.
type: landing  # Page type is a Widget Page

sections:
  - block: about.biography
    id: about
    content: 
      title: Bio
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '2'
      view: compact
  - block: experience 
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Graduate Instructor
          company: Texas Tech University
          company_url: ''
          company_logo: 
          location: Texas
          date_start: '2023-08-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Lecturing
              * Preparing Homework and slides
              * Grading ~100 students
              * Exam creation 
        - title: Teaching Assisent  
          company: Texas Tech University
          company_url: ''
          company_logo: 
          location: Texas
          date_start: '2021-08-01'
          date_end: '2023-08-01'
          description: Grading exams, met with students, provided supplemental notes
    design:
      columns: '1'
      background:
      gradient_start: '#3D080C'
      gradient_end: '#070B10'
      gradient_angle: 90
---