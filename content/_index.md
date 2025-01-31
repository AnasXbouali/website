---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-01-31
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin  # Ensure your profile exists in `content/authors/admin/`
      text: |
        Since September 2024, I am a postdoctoral researcher at INRAE Occitanie-Montpellier, as a member of UMR MISTEA working with Alain Rapaport (Senior Researcher at INRAE Montpellier). I specialize in applied mathematics, with a focus on optimal control and optimization, particularly in hybrid systems. My research applies these techniques to areas such as modeling and epidemiology.

        Before that, from September 1, 2023 to August 31, 2024, I was a ATER (Temporary Lecturer and Research Assistant) at Avignon Université.

        Prior to that, from October 1, 2020, to November 17, 2023, I was a PhD student at Avignon Université. My PhD supervisors were Térence Bayen (Prof. at Avignon Université) and Loïc Bourdin (MCF HDR at Limoges Université). My research involved the derivation of first-order necessary optimality conditions for optimal control problems involving spatially heterogeneous dynamics and their applications to optimal control problems with loss control regions.
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: '📚 My Research'
      text: |-
        I am a postdoctoral researcher at the MISTEA research unit (INRAE, Institut Agro), Montpellier, France. 
        My research focuses on optimal control and optimization, particularly in hybrid systems, and their applications to modeling and epidemiology.

        Please reach out to collaborate at **anas.bouali@inrae.fr**.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: markdown
    content:
      title: '📝 Featured Research Paper'
      text: |-
        **Title:** On the Use of Needle-Like Perturbations in Spatially Heterogeneous Control Systems  
        **Authors:** Anas Bouali, Terence Bayen, Loïc Bourdin  
        **Published In:** *Journal of Optimization Theory and Applications, Vol. 204, No. 46, 2025*  
        [Read the Paper](https://link.springer.com/article/10.1007/s10957-025-02607-6)
    design:
      columns: '1'

  - block: markdown
    content:
      title: '📬 Contact Me'
      text: |-
        - **Email:** anas.bouali@inrae.fr  
        - **GitHub:** [AnasXbouali](https://github.com/AnasXbouali)  
        - **Google Scholar:** [My Publications](https://scholar.google.com/citations?user=CdSC_JsAAAAJ&hl=fr&oi=ao)  
        - **LinkedIn:** [My Profile](https://www.linkedin.com/in/anas-bouali-276539215/?originalSubdomain=fr)  

        Feel free to reach out for collaborations or discussions!
    design:
      columns: '1'
---
