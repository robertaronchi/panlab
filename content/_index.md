---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Corrado Corradi-Dell'Acqua
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 1
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
      columns: '2'
  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

  - block: collection
    content:
      title: Ongoing Projects
      subtitle:
      text:
      count: 1
      filters:
        folders:
          - project      
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '2'

  - block: collection
    content:
      title: Featured Papers
      text: ""
      filters:
        folders:
          - publication
        publication_type: "2"
        featured_only: true
    design:
      view: Card
      columns: '2'

  - block: tag_cloud
    content: 
      title: Popular Topics
      subtitle:
      content:
        # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
        taxonomy: tags
        # Choose how many tags you would like to display (0 = all tags)
        count: 20
    design:
      font_size_min: 0.7
      font_size_max: 2.0
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '2'

---
