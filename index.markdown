---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

author_profile: true
title: "Welcome to my portfolio site!"
layout: collection
# collection: portfolio
entries_layout: grid
classes: wide

feature_row:
 
  - image_path: assets/images/education.jpg
    title: "Education"
    url: "/portfolio/education"
    btn_class: "btn--primary"  
  - image_path: assets/images/skills.jpg
    title: "Skills"
    url: "/portfolio/skills"
    btn_class: "btn--primary"
  - image_path: assets/images/experience.jpg
    url: "/portfolio/experience"
    title: "Experience"
    btn_class: "btn--primary"
  - image_path: assets/images/interest.jpg
    title: "Interest"
    url: "/portfolio/interest"
    btn_class: "btn--primary"
---
{% include feature_row %}
