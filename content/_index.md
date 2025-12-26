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
        align: right
        background:
          image:
            filename: shrestha_lab_helix_dark_extended.png
            filters:
              brightness: 0.3
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
        filename: lab_banner_welcome_2.png
        position: center
      text: |
        <br>
        
        The **Shrestha Lab** is a computational cancer genomics and data science research group at the **[Center for Prostate Disease Research (CPDR)](https://sites.google.com/usuhs.edu/cpdr)**. We focus on elucidating the drivers of cancer progression and therapeutic resistance, with the goal of advancing personalized medicine and improving clinical outcomes for prostate cancer patients by understanding the complex interplay of the genome, transcriptome, proteome, and epigenome.

        {{% cta cta_link="./research/" cta_text="Learn more →" %}}
 
  - block: features
    content:
      title: Our Research Arms
      text: "Our research will focus on three major avenues"
      items:
        - name: "Develop"
          description: "**Algorithm Development**: Develop cutting-edge computational genomics and machine learning methods to unravel the complexities of cancer"
          icon: "networkx-original"
          icon_pack: custom
        - name: "Mine"
          description: "**Data Mining & Analytics**: Mine, Integrate & Analyze complex multi-modal biological datasets to understand context-specific genome regulation in cancer"
          icon: "chartjs-original"
          icon_pack: custom
        - name: "Translate"
          description: "**Translational Bioinformatics**: Translate genomic insights to meaningful clinical applications for precision oncology"
          icon: "jekyll-original"
          icon_pack: custom
    design:
      columns: "3"
      background:
        color: "gray-50"

  - block: markdown
    content:
      title: Our Affilations
      subtitle: 
      text: | 
        We are located at the **[Center for Prostate Disease Research (CPDR)](https://sites.google.com/usuhs.edu/cpdr)** under the [Henry M Jackson Foundation for the Advancement of Military Medicine (HJF)](https://www.hjf.org) in Bethesda, Maryland. Our lab is a part of [Murtha Cancer Center Reseaerch Program (MCCRP)](https://medschool.usuhs.edu/sur/research/murtha-cancer-center) and [Walter Reed National Military Medical Center (WRNMMC)](https://walterreed.tricare.mil/MurthaCancerCenter).
        
        Academically, we are primarily affiliated with the [Uniformed Services University of the Health Sciences (USUHS)](https://www.usuhs.edu), [Dept. of Surgery](https://medschool.usuhs.edu/sur), with a secondary affiliation at the [Genitourinary Malignancies Branch (GMB)](https://ccr.cancer.gov/genitourinary-malignancies-branch), [National Cancer Institute (NCI)](https://ccr.cancer.gov).
        
      position: top
      color: "#000000"
    design:
      columns: '1'
      background:
        color: "gray-50"
  
  - block: markdown
    content:
      title: 
      subtitle: 
      text:
      position: top
      color: "#000000"
    design:
      columns: '1'
      background:
        image: 
          filename: org_logo_combo.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: 1200px
          text_color_light: false
        spacing:
          padding: ['20px', '20px', '20px', '20px']

---
