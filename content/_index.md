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
        folders:
          - news
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
  
  - block: markdown
    content:
      title: Test
      subtitle: 'Sub-test'
      text: Black blah blah
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

---