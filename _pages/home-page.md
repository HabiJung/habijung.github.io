---
title: "Welcome :: BIN_ ::"
permalink: /home/
layout: splash
redirect_from: /
date: 2021-08-13T01:35
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/img-pages/home-main-1600x1200.jpg
  actions:
    - label: "About"
      url: "/about/"
  caption: "© 2020 Iceland by Habi Jung"
excerpt: "Thanks for visiting my blog<br>Check my profile & blog description here"
intro: 
  - excerpt: 'Welcome to Blog **:: BIN_ ::**<br>I hope you get the information you want my blog.<br>If you have any questions, please contact me, **<habijnug0@gmail.com>**'

feature_row:
  - image_path: assets/images/img-pages/home-gallery-1-600x400.jpeg
    image_caption: "© [Link](https://medium.com/digital-bulletin/the-route-to-better-software-testing-d21143f1538a)"
    alt: "placeholder image 1"
    title: "Computer Science"
    excerpt: "**Academic Student** @ [**UNIST**](https://unist.ac.kr)<br>Department of **Computer Science** and **Engineering**"

  - image_path: /assets/images/img-pages/home-hallery-2-600x400.jpg
    image_caption: "© [Link](https://sites.google.com/site/greenmonkeystm/home/graphics-and-visual-computing-1)"
    alt: "placeholder image 2"
    title: "Computer Graphics"
    excerpt: "Interested in **Computer Graphics**, **3D Modeling**, etc."

  - image_path: /assets/images/img-pages/home-gallery-3-600x400.jpg
    image_caption: "© [Link](https://www.eba250.com/actions-projects/business-investment-platform/)"
    alt: "placeholder image 3"
    title: "Investment"
    excerpt: "Being **Financially Independent**"

feature_row2:
  - image_path: /assets/images/img-pages/gallery-1-600x400.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "/year-archive/"
    btn_label: "[ Posts ]"
    btn_class: "btn--primary"

feature_row3:
  - image_path: /assets/images/img-pages/gallery-2-600x400.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "/categories/"
    btn_label: "[ Categories ]"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /assets/images/img-pages/gallery-3-600x400.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "/tags/"
    btn_label: "[ Tags ]"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}