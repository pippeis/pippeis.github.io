---
permalink: "/"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/home-splash.jpg
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: /assets/images/box-1.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/courses/course_1"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row-2:
  - image_path: /assets/images/box-2.jpg
    id: "row2"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/courses/course_2"
    btn_label: "Read More"
    btn_class: "btn--inverse"
feature_row-3:
  - image_path: /assets/images/box-3.jpg
    id: "row3"
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/courses/course_3"
    btn_label: "Read More"
    btn_class: "btn--inverse"
---

<div class="feature-row-container">
    {% include feature_row type="left" %}

    {% include feature_row id="feature_row-2" type="right" %}
    
    {% include feature_row id="feature_row-3" type="left" %}
</div>
