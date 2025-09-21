---
# Leave the homepage title empty to use the site title
title: Shrestha Lab
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: We are under construction!
        content: stay tuned ...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: hero
    content:
      title: |
        Shrestha Lab at CPDR
      image:
        filename: shrestha_lab_helix_dark_extended.png
        position: center
      text: |
        <br>
        
        The **Shrestha Lab** at the **[Center for Prostate Disease Research (CPDR)](https://sites.google.com/usuhs.edu/cpdr)** focuses on elucidating the drivers of cancer progression and therapeutic resistance through innovative strategies in computational genomics and machine learning, with the goal of advancing personalized medicine and improving clinical outcomes for prostate cancer patients by understanding the complex interplay of the genome, transcriptome, proteome, and epigenome.
 
  - block: features
    content:
      title: 
      text: "Our research will focus on three major avenues"
      items:
        - name: "Develop"
          description: "Develop cutting-edge computational genomics and machine learning methods to unravel the complexities of cancer"
          icon: "networkx-original"
          icon_pack: custom
        - name: "Integrate & Analyze"
          description: "Integrate & Analyze complex multi-modal biological datasets to understand context-specific genome regulation in cancer"
          icon: "chartjs-original"
          icon_pack: custom
        - name: "Translate"
          description: "Translate genomic insights to meaningful clinical applications for precision oncology"
          icon: "jekyll-original"
          icon_pack: custom
    design:
      columns: "3"
      background:
        color: "gray-50"

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
