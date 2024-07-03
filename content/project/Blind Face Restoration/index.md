---
title: TFRGAN Leveraging Text Information for Blind Face Restoration with Extreme Degradation
summary: Using text information to achieve better res in BFR task.(This work has been submitted to CVPR workshop)
tags:
  - Deep Learning
date: '2022-11-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: The transfer result showing
  focal_point: Smart

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Blind face restoration, which aims to recover high-quality face images from degraded low-quality inputs, is a challenging problem in the field of image processing and computer vision. Although existing methods based on geometric or generative priors have shown promising results, restoring severely degraded faces remains a difficult task. In response to this challenge, we propose a novel approach called TFRGAN, which incorporates textual information to enhance the restoration of extremely degraded face images.

Our TFRGAN approach seeks to generate a more accurate and effective latent code for the StyleGAN2 prior by fusing textual and image information in the latent code space. Furthermore, the extracted textual features are utilized to modulate the decoding features, resulting in more realistic and natural facial images with plausible details. Our experimental results demonstrate the superiority of our proposed method in restoring severely degraded face images.
