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
  - block: markdown
    id: section-1
    content:
      title: Teaching
      text: 
        <h3>The Pennsylvania State University (Instructor)</h3>
        <ul>
          <li>Introduction to Econometrics (U)</li>
        </ul>
        <h3>The Pennsylvania State University (TA)</h3>
        <ul>
          <li>**Econometrics** (PhD) for J. Pinkse</li> 
        </ul>
    design:
      columns: '2'
---
