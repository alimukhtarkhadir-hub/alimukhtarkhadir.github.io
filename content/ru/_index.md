---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Скачать резюме
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: '📚 Мои исследования'
      subtitle: ''
      text: |-
        Я студент первого курса направления «Прикладная информатика» в РУДН. Патриот Кении, увлечённый кибербезопасностью, искусственным интеллектом и программированием.

        Моя цель — получить знания и навыки, чтобы вернуться на родину и внести вклад в развитие Кении.

        Пишите — рад к сотрудничеству 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Избранные публикации
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Последние публикации
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Последние и предстоящие выступления
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Последние новости
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
