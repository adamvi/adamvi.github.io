---
layout: default
title: Home

navbar:
  - name: About Me
    link: '#fakeAboutLink'

  - name: Pages
    menu: true
    - label: Main Item 1
      link:  '#fakeLink1'
    - label: Main Item 2 - Sub Menu
      link:  404.html
      submenu: true
      - label: Sub-Item 1
        link:  404.html
      - label: Sub-Item 2
        link:  404.html
      - label: Sub-Item 3
        link:  404.html
    - label: Main Item 3
      link:  404.html

  - name: Contact Me
    link: '#fakeContactLink'


contents:
  - location: center
    description: SASQUATCH!
    image: images/DIY_Skilz/yeti_253x292.png

  - location: upper_left
    description: Open Source Development
    image: images/DIY_Skilz/opensourcerer_253x292.png
    link: https://github.com/adamvi
    
  - location: upper_right
    description: Research and Projects
    image: images/DIY_Skilz/datavisionary_253x292.png
    link: research.html

  - location: center_left
    description: My Blog
    image: images/DIY_Skilz/illustrator_253x292.png
    link: blog.html

  - location: center_right
    description: Academics and CV
    image: images/DIY_Skilz/entrepreneur_253x292.png
    link: academics.html

  - location: lower_left
    description: My Life in Pictures
    image: images/DIY_Skilz/photographer_253x292.png
    link: photo_albums.html

  - location: lower_right
    description: All Things Food
    image: images/DIY_Skilz/chef_253x292.png
    link: food_cooking.html

footer_social:
  - type: github
    link: https://github.com/adamvi
    image: images/social-icon/github.png

  - type: linkedin
    link: my.linkedin.handle
    image: images/social-icon/linkedin.png

  - type: twitter
    link: my.twit.handle
    image: images/social-icon/twitter.png
---
{% include JB/setup %}

Copyright © 2013 Adam Vaniwaarden. All rights reserved. This site is powered by [Jekyll](http://jekyllrb.com/) and hosted on [GitHub Pages](https://github.com) using the [Hive theme](https://github.com/adamvi/hive) for [Jekyll Bootstrap](http://jekyllbootstrap.com).