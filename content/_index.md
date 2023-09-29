---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Hello World
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 
      icon: r-project
      icon_pack: fab
      name: Data analysis & web applications
    - description: 
      icon: chart-line
      icon_pack: fas
      name: Socio-ecological systems modeling
    - description: 
      icon: pen-nib
      icon_pack: fas
      name: Nature & environmental writing
    title: Skills
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: contact
  content:
    email: 
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    phone: 
    subtitle: null
    text: You can write to me here.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
