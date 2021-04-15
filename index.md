---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash.jpg
excerpt: ""
intro:
  - image_path: /assets/images/bio-photo2.jpg
    title: Briefly About Me
    excerpt: "Teacher turned data scientist passionate about coding and it's applications."
feature_row:
  - image_path: _portfolio/beer_images/title.JPG
    alt: "placeholder image 1"
    title: "Beer Price Checker"
    excerpt: "An app for comparing prices of beer."
    url: /portfolio/beer
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: _portfolio/kickstarter_images/title.JPG
    alt: "placeholder image 2"
    title: "Kickstarting Kickstarter"
    excerpt: "Can we predict which Kickstarters will be successful?"
    url: /portfolio/kickstarter
    btn_label: "Read More"
    btn_class: "btn--primary"
    
gallery:
  - url: /portfolio/beer
    image_path: _portfolio/beer_images/title.JPG
    alt: "Beer Price Checker"
    title: "Beer Price Checker"
  - url: /portfolio/kickstarter
    image_path: _portfolio/kickstarter_images/title.JPG
    alt: "Kickstarting Kickstarter"
    title: "Kickstarting Kickstarter"
  - url: /portfolio/kickstarter
    image_path: /assets/images/splash.jpg
    alt: "placeholder image 3"
    title: "NBA All Star Predictor"
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "NBA All Star Predictor"
    excerpt: "Find out what it takes to be an NBA All Star."
    url: /portfolio/kickstarter
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
## Portfolio Projects
{% include gallery type="center" %}

