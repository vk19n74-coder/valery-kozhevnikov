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
      css_class: ""

  - block: markdown
    id: research
    content:
      title: Research
      text: |
        Our group works at the interface of synthetic inorganic chemistry, photophysics, 
        and materials science. Current research themes include:

        **Phosphorescent Metal Complexes**  
        Design and synthesis of Ir(III), Ru(II), Re(I), and Eu(III) complexes as emitters 
        for OLEDs, bioimaging, and photocatalysis.

        **TADF in Rh(III) Complexes**  
        Thermally activated delayed fluorescence in earth-abundant metal complexes as 
        sustainable alternatives to iridium-based emitters.

        **Bioorthogonal IEDDA Chemistry**  
        1,2,4-Triazine reagents for inverse electron demand Diels-Alder ligation in live 
        cells, with applications in nuclear medicine pretargeting and metabolic 
        glycoengineering.

        **Luminescent Solar Concentrators**  
        Eu(III) complexes in polymer matrices (~615 nm emission) for building-integrated 
        photovoltaics (BIPV) in partnership with North East England industry.

        **Acoustic Wave Modulation**  
        Surface-immobilised Ir(III) and Ru(II) catalysts on LiNbO₃ substrates modulated 
        by surface acoustic waves.
    design:
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Recent Publications
      count: 5
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
      columns: '1'

  - block: collection
    id: news
    content:
      title: Latest News
      count: 3
      filters:
        folders:
          - post
    design:
      view: card
      columns: '1'

  - block: people
    id: team
    content:
      title: Team
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
      directions: Northumbria University City Campus, Newcastle upon Tyne
    design:
      columns: '1'
---
