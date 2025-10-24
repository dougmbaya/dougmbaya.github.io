---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '1.5rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      css_style: 'padding-top: 0 !important; margin-top: -5rem !important;'
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: resume-experience
    content:
      username: admin
      show_education: false
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: markdown
    content:
      title: '☁️ My Mission'
      subtitle: ''
      text: |-
        I'm a strategic architect driving innovation at the intersection of cloud technology, AI/ML, and partner ecosystems. At AWS, I lead technical integrations that accelerate partner go-to-market strategies and deliver measurable business impact.

        My expertise spans generative AI architecture, data analytics pipelines, and hybrid cloud solutions. I'm passionate about enabling partners to build transformative solutions that drive real-world outcomes.

        Let's collaborate on your next cloud innovation project! �
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="display: flex; justify-content: center; margin: 2rem 0;">
          <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6899098617278279680?collapsed=1" height="479" width="504" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: talks
    content:
      title: Recent & Upcoming Talks
      subtitle: ''
      text: |-
        <style>
          .talks-grid { 
            display: grid; 
            grid-template-columns: repeat(2, 1fr); 
            gap: 2rem; 
            width: 100%; 
            max-width: 100%;
            align-items: start;
          }
          .talks-grid iframe { width: 100%; }
        </style>
        <div class="talks-grid">
          <div>
            <iframe width="100%" height="500" src="https://www.youtube.com/embed/sQmWq0P5wNI?si=A0A63NoUEVaNYIQr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
          </div>
          
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7386038531695218688?collapsed=1" height="700" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
          
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7076831043495870464" height="700" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: |-
        <style>
          .news-grid { 
            display: grid; 
            grid-template-columns: repeat(2, 1fr); 
            gap: 2rem; 
            width: 100%; 
            max-width: 100%;
            align-items: start;
          }
          .news-grid iframe { width: 100%; }
        </style>
        <div class="news-grid">
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7378967367785177088?collapsed=1" height="750" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
          
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7338558748099006464" height="900" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
          
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7325905070019997697" height="500" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
          
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7325659861927493633?collapsed=1" height="600" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
          
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7241470423249383426?collapsed=1" height="750" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
          
          <div>
            <iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:7179261206837280768?collapsed=1" height="650" width="100%" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>
          </div>
        </div>
    design:
      columns: '1'
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
