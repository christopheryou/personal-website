---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: pages
    content: 
      CV: /cv/_index.md
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |-
        <p><typewritten-text letter-interval="50">👋 Hi, there! I'm <strong>Chris</strong>, a third year PhD student @ the University of Florida. I'm researching virtual humans and machine learning with Dr. Benjamin Lok.</typewritten-text></p>
        {<link rel="stylesheet" href="https://unpkg.com/@auroratide/typewritten-text/lib/style.css" />
        <script type="module" src="https://unpkg.com/@auroratide/typewritten-text/lib/define.js"></script>}
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          # style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"
          filename: space.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
      css_class: d-flex fullscreen align-items-center

[My CV]({{< relref "/cv/_index" >}})
      
---
