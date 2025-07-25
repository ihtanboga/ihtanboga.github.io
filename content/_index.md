---
title: 'Home'
date: 2023-10-24
type: landing
sections:
  - block: resume-biography
    content:
      username: admin
    design:
      spacing:
        padding: ['20px', 0, '20px', 0]
      biography:
        style: 'text-align: justify; font-size: 0.9em;'
  - block: resume-interests  
    content:
      username: admin
      title: Research Interests
    design:
      spacing:
        padding: ['20px', 0, '20px', 0]
  - block: resume-education
    content:
      username: admin
      title: Education
    design:
      spacing:
        padding: ['20px', 0, '20px', 0]
  - block: resume-experience
    content:
      username: admin
      title: Experience
    design:
      spacing:
        padding: ['20px', 0, '30px', 0]
  - block: collection
    id: recent-posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      count: 5
      filters:
        folders:
          - blog
        exclude_featured: false
      archive:
        enable: true
        text: View all posts
        link: blog/
    design:
      spacing:
        padding: ['30px', 0, '30px', 0]
      view: compact
      columns: '1'
---
