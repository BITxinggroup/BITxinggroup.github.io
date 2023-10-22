---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text:  Welcome outstanding students who are interested in scientific research to join our laboratory!    # 欢迎有志于科研的优秀学子加入本实验室！
      email: chengwenxing@bit.edu.cn   
      directions: shiqigong@bit.edu.cn          # 巩世琪副教授
      # phone: 888 888 88 88
      # address: 北京市海淀区中关村南大街5号院  北京理工大学
      # # address: 邢成文教授： 10#609(信息科学实验楼609)
      # # address: 巩世琪副教授： 中心教学楼544
      #   street: 中关村南大街5号院北京理工大学  邢成文教授： 10#609(信息科学实验楼609)   巩世琪副教授： 中心教学楼544
      #   city: 海淀区
      #   region: 北京
      #   postcode: '100081'
      #   country: 中国
      #   country_code: CN

      coordinates:
        latitude: '39.957489'
        longitude: '116.319175'
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
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
          filename: 实验室.png
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
