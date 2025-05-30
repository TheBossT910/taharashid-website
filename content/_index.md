---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
      # TODO: add resume link (Google Drive?)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: bg.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 A bit about myself'
      subtitle: ''
      text: |-
        👋 Hey, I’m Taha Rashid!

        I’m a first-year Software Engineering student at the University of Ottawa.

        I’m currently just finished developing Koyomi AnimeTracker, an iOS/iPadOS 📱, MacOS 💻 and VisionOS 🥽 app that helps users track anime episode release schedules. This project has been an exciting challenge and a great way to learn and apply Swift, SwiftUI, Python, Firebase, and API integrations to a real problem I had.
    design:
      columns: '1'

  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Posts
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
 
  - block: collection
    id: news
    content:
      title: Posts
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
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
      view: article-grid
      columns: 2
      # Reduce spacing
      # spacing:
      #   padding: [0, 0, 0, 0]
---
