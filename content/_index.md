---
# Leave the homepage title empty to use the site title
title:
date: 2023-07-08
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome everyone!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: Publications
    content:
      title: Publications
      # text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: News
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: Experience
    id: Experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Scientist Intern
          company: MIT-IBM Watson AI Lab
          company_url: ''
          # company_logo: org-gc
          location: Cambridge, MA
          date_start: '2025-06-02'
          date_end: 
          description: AI-Assisted Decision Making.
        - title: Communication Fellow
          company: Massachusetts Institute of Technology
          company_url: ''
          # company_logo: org-gc
          location: Cambridge, MA
          date_start: '2024-01-01'
          date_end: 
          description: Coaching MIT students on their communication abilities in scientific writing, talks, and posters.
        - title: Teaching Assistant
          company: Duke University
          company_url: ''
          # company_logo: org-gc
          location: Durham, NC
          date_start: '2021-01-01'
          date_end: '2023-08-12'
          description: Three terms of teaching assistant for Intro to Data Science (STA199) and Mathematical Statistics (STA432).
        - title: Data Scientist
          company: Emergo Therapeutics
          company_url: ''
          # company_logo: org-gc
          location: Morrisville, NC
          date_start: '2021-06-01'
          date_end: '2021-09-01'
          description: Analyzed clinical trial data, contributing insights guiding Emergo's decision-making process in clinical trials.
        - title: Intern
          company: Lenovo
          company_url: ''
          # company_logo: org-gc
          location: Morrisville, NC
          date_start: '2019-05-01'
          date_end: '2019-08-01'
          description: 
    design:
      columns: '2'
  - block: features
    id: Skills
    content:
      title: Skills
      items:
        - name: Python + PyTorch
          description: 4 years experience
          icon: python
          icon_pack: fab
        - name: R
          description: 4 years experience
          icon: r-project
          icon_pack: fab
        - name: LaTeX
          description: 4 years experience
          icon: chart-line
          icon_pack: fas
    design:
      columns: '2'
      view: compact

---
