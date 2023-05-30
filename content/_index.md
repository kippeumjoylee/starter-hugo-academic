---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: research
    content:
      title: Research
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: teaching
    content:
      title: Teaching
      text: 
       ### University of Chicago (TA)
        - **Spatial Economics** (PhD) for E. Rossi-Hansberg
        - **Theory of Income III** (PhD) for F. Alvarez
        - **International Trade** (U) for F. Tintelnot
        - **Managing the Firm in the Global Economy** (MBA) for J. Dingel
        - **Financial Markets in the Macroeconomy** (PhD) for V. Guerrieri
        - **International Financial Policy** (MBA) for R. Kekre

       ### Duke University (TA)
        - **Intermediate Macroeconomics** (U) for M. Connolly
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
