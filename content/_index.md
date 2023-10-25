---
# Leave the homepage title empty to use the site title
title: DanceGroup
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        DANCE
      image:
        filename: team.jpg
      text: |
        <br>
        (Data And Network CoordinatE) Group
  
  - block: collection
    content:
      title: Latest Project
      subtitle:
      text:
      count: 3
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
          filename: team.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle: Want to know more ?
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---

# 