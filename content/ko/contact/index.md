---
title: Contact

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: ''
      email: yang_bun@jbnu.ac.kr
      phone: 010-4332-9597
      address:
        region: 전북특별자치도
        city: 전주시
        street: 전북대학교 공과대학 7호관
        postcode: '54896'
        country: 대한민국
        country_code: KO
      coordinates:
        latitude: '35.84601324617979'
        longitude: '127.13444961966684'
      directions:
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'

      # Automatically link email and phone or display as text?
      autolink: true

      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
      
    design:
      columns: '3'

  - block: contact
    content:
      title: 문의
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: false
          
    design:
      columns: '3'
---
