---
title: Головна
sections:
  - type: heroblock
    template: heroblock
    section_id: hero
    component: hero_block.html
    content: >-
      У цьому блозі я буду викладати свої відео на YouTube.
  - type: contentblock
    template: contentblock
    title: Про мене
    section_id: about
    actions:
      - label: Зв’язатися зі мною
        url: /contact
    component: content_block.html
    content: >-
      Я Богдан. Люблю свого хом’ячка та викладати відео на YouTube.
  - type: postsblock
    template: postsblock
    title: Останні пости
    section_id: recent-posts
    actions:
      - label: Переглянути блог
        url: blog/index.html
    component: posts_block.html
    num_posts_displayed: 4
menu:
  main:
    name: Головна
    weight: 1
layout: home
---
