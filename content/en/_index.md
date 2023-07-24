---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Welcome!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        This is the official website of the joint MSc in Electronics and Technology between the [Cyprus University of Technology](https://cut.ac.cy) in Cyprus and the [Hangzhou Dianzi University](https://www.hdu.edu.cn) in China.
  
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
      view: compact
      columns: '2'
  
  - block: features
    content:
      title: My Interests
      subtitle: Section subtitle
      text: Section text
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
---