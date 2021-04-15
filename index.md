---
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
excerpt: ""
intro:
  - image_path: /assets/images/bio_photo2.jpg
    title: "Alex Li"
    excerpt: "Data Scientist"
feature_row:
  - image_path: _portfolio/beer_images/title.JPG
    alt: "placeholder image 1"
    title: "Beer Price Checker"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: /portfolio/beer
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: _portfolio/kickstarter_images/title.JPG
    alt: "placeholder image 2"
    title: "Kickstarting Kickstarter"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: /portfolio/kickstarter
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "NBA All Star Predictor"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
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

{% include feature_row id="feature_row" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
