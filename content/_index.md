---
title: 'Haruto Kobayashi'
date: 2025-02-12
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download Résumé
      #   url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  - block: awards
    content:
      title: Awards
      username: admin
  # - block: languages
  #   content:
  #     title: Languages
  #     username: admin
  - block: publication
    content:
      title: Publication
      username: admin
    #   title: Publications
    #   subtitle: ''
    #   text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    #   # Display content from the `content/post/` folder
    #   filters:
    #     folders:
    #       - publication
    # design:
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
    #   # Choose your content listing view - here we use the `showcase` view
    #   view: citation
    #   # For the Showcase view, do you want to flip alternate rows?
    #   # flip_alt_rows: true
---
