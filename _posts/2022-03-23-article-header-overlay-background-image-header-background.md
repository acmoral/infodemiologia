---
layout: article
title: Post 8
permalink: /page/article-header-overlay-background-image-header-background.html
key: page-article-header-overlay-background-image-HB
cover:  /assets/images/cover3.jpg
header:
  theme: dark
  background: 'linear-gradient(135deg, rgb(34, 139, 87), rgb(139, 34, 139))'
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(135deg, rgba(34, 139, 87, .4), rgba(139, 34, 139, .4))'
    src: /docs/assets/images/cover3.jpg
---

A post has an article header overlay with a background image width customized header background.

<!--more-->

<style>
  .page__header .header__brand path {
    fill: rgba(255, 255, 255, .95);
  }
</style>

**front matter:**

    ---
    layout: article
    title: Page - Article Header Overlay Background Image (Customized Header Background)
    header:
      theme: dark
      background: 'linear-gradient(135deg, rgb(34, 139, 87), rgb(139, 34, 139))'
    article_header:
      type: overlay
      theme: dark
      background_color: '#203028'
      background_image:
        gradient: 'linear-gradient(135deg, rgba(34, 139, 87 , .4), rgba(139, 34, 139, .4))'
        src: /docs/assets/images/cover3.jpg
    ---
