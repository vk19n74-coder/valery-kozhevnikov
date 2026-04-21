---
title: Home
type: landing

sections:
 - block: hero
    content:
      title: Kozhevnikov Lab
      text: |
        **Luminescent Coordination Chemistry at Northumbria University**

        We design and synthesise phosphorescent and TADF metal complexes for applications 
        in OLEDs, luminescent solar concentrators, and bioorthogonal chemical biology.
      cta:
        label: Meet the Team
        url: '#team'
      cta_alt:
        label: Our Research
        url: '#research'
    design:
      background:
        color: white
   
  - block: markdown
    id: research
    content:
      title: Research
      text: |
        Our group works at the interface of synthetic inorganic chemistry, photophysics, and 
        materials science. Current research themes include:

        - **Phosphorescent complexes** — Ir(III), Ru(II), Re(I), and Eu(III) complexes as 
          emitters for OLEDs and bioimaging
        - **TADF** — Thermally activated delayed fluorescence in Rh(III) complexes
        - **Bioorthogonal chemistry** — 1,2,4-triazine reagents for inverse electron demand 
          Diels-Alder (IEDDA) ligation in live cells and nuclear medicine pretargeting
        - **Luminescent Solar Concentrators** — Eu(III) complexes in polymer matrices 
          for building-integrated photovoltaics
        - **Surface catalysis** — Acoustic wave modulation of surface-immobilised 
          metal complexes on LiNbO₃
    design:
      columns: '1'

  - block: collection
    id: news
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        folders:
          - post
    design:
      view: card
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text:
      count: 5
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
      columns: '1'

  - block: markdown
    id: team
    content:
      title: Team
      text: |
        Meet the members of the Kozhevnikov Lab.
    design:
      columns: '1'

  - block: people
    content:
      title: ""
      user_groups:
        - Principal Investigator
        - Researchers
        - PhD Students
        - Visitors
        - Alumni
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: contact
    id: contact
    content:
      title: Contact
      text:
      email: valery.kozhevnikov@northumbria.ac.uk
      address:
        street: Department of Applied Sciences, Northumbria University
        city: Newcastle upon Tyne
        postcode: NE1 8ST
        country: United Kingdom
        country_code: GB
      coordinates:
        latitude: '54.9783'
        longitude: '-1.6178'
    design:
      columns: '1'
---
