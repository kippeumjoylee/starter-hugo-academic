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
    id: teaching
    content:
      title: Teaching
      text: 
        <h3>The Pennsylvania State University (Instructor)</h3>
        <ul>
          <li>Introduction to Econometrics (U), Summer 2022</li>
        </ul>
        <h3>The Pennsylvania State University (TA)</h3>
        <ul>
          <li><strong>Econometrics </strong> (PhD) for J. Pinkse, Spring 2022 - Fall 2022</li>
          <li><strong>Econometrics </strong> (PhD) for P. Guggenberger, Fall 2021</li> 
          <li><strong>Money and Banking </strong> (U) for R. Chuderewicz, Fall 2018 - Spring 2021 </li>
        </ul>
        <h3>Korea University (TA)</h3>
        <ul>
          <li><strong>Micro-econometrics</strong> (G) for M.J. Lee, Fall 2017</li>
          <li><strong>Econometrics I</strong> (U) for M.J. Lee, Spring 2017</li> 
        </ul>
    design:
      columns: '2'
---
