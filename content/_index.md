---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: https://drive.google.com/file/d/16ESyiKcAISSFxjB069ftI_tqlv0mLqlK/view?usp=drive_link
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: banner.png
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.7em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: awards
    content:
      title: Select Publications
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
