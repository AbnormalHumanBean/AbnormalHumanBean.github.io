---
title: "Welcome to Me" 
date: 2024-01-01
type: landing

sections:
- block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin     
  - block: experience
    id: exp
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Instructor
          company: Texas Tech University
          company_url: ''
          company_logo: icon
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
          company_logo: icon
          location: Texas
          date_start: '2021-08-01'
          date_end: '2023-08-01'
          description: Grading exams, met with students, provided supplemental notes
    design:
      columns: '1'     
---