---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Навыки
      items:
        - name: C++
          description: средний
          icon: file-code
          icon_pack: fas
        - name: HTML, CSS
          description: средний
          icon: laptop-code
          icon_pack: fas
        - name: Markdown
          description: выше среднего
          icon: markdown
          icon_pack: fab

  - block: experience
    content:
      title: Опыт
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Среднее общее образование
          company: Лицей
          company_url: ''
          company_logo: 
          location: Молдова
          date_start: '2009-09-01'
          date_end: '2022-06-20'
          description: Обучение в начальной школе, гимназии, лицее
        - title: Бакалавриат
          company: Российский университет дружбы народов
          company_url: ''
          company_logo: 
          location: Москва, Россия
          date_start: '2022-09-01'
          date_end: ''
          description: Факультет физико-математических и естественных наук
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Достижения'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: '2022-05-01'
          date_start: '2021-09-01'
          description: 'Курс по графическому дизайну'
          organization: Tekwill
          organization_url: https://tekwill.md/
          title: Графический дизайн
          url: ''
        - certificate_url: 
          date_end: '2022-10-20'
          date_start: '2022-09-05'
          description: Курс по основам программирования на языке C++
          organization: Stepik
          organization_url: https://stepik.org/
          title: Основы программирования на C++
          url: ''

    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Недавние посты
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Проекты
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: Все
          tag: '*'
        - name: Учеба
          tag: 'education'
        - name: Другие
          tag: 'other'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
 # - block: markdown
 #   content:
  #    title: Gallery
 #     subtitle: ''
  #    text: |-
   #     {{< gallery album="demo" >}}
   # design:
    #  columns: '1'
 # - block: collection
 #   id: featured
  #  content:
   #   title: Featured Publications
    #  filters:
     #    folders:
      #   - publication
       #  featured_only: true
   # design:
    #  columns: '2'
    #  view: card
 # - block: collection
  #  content:
   #   title: Recent Publications
    #  text: |-
     #   {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications(.publication/).
      #  {{% /callout %}}
     # filters:
      #  folders:
       #   - publication
       # exclude_featured: true
    # design:
     # columns: '2'
    #  view: citation
  
  
  - block: contact
    id: contact
    content:
      title: Контакт
      subtitle:
      text: |-
        Связаться
      # Contact (add or remove contact options as necessary)
      email: galatsan.2003@mail.ru
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 
        city: Москва
        region: Россия
        postcode: ''
        country: Russia
        country_code: Russia
     
      
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
      columns: '2'
---
