---
title: My page
type: landing

sections:
  - block:
    id:
    content:
      title: Welcome
      subtitle:
      text:
    design:
      columns: '1'
      background:
        image: Beloi_2015.jpg  # in assets/media
        image_darken: 0.5  # range 0-1, close to 0 is darker
        image_parallax: true
        image_position: center
        image_size: cover
        text_color_light: true
        spacing:
        padding: ['110px', '0', '0', '0']
    advanced:
      css_class: fullscreen
  - block: accomplishments
    content:
      title: Accomplishments
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Neural Networks and Deep Learning
          certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          url: ''
        - title: Blockchain Fundamentals
          certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - title: 'Object-Oriented Programming in R'
          certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          url: ''
          design:
          # Choose how many columns the section has. Valid values: '1' or '2'.
          columns: '2'
---
