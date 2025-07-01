---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-07-01
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '🧬 Bioinformatics & Data Visualization'
      subtitle: ''
      text: |-
        I'm a Master's student in Bioinformatics at the University of Copenhagen, with a focus on genomic data, machine learning, and visual storytelling.

        My work bridges science and design: I build reproducible pipelines, run in-depth analyses, and craft visualizations that help make complex biological data understandable and impactful. I work primarily in R, Python, and Snakemake.

        While I remain committed to research and open science, I'm also building a career in freelance data visualization and scientific communication. If you're looking for someone who can make your data clear, compelling, and scientifically grounded—I'd love to hear from you.

    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Featured Projects
      filters:
        folders:
          - project
        featured_only: false
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
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
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
