---
title: Learning 3D skin and skeleton models from CT scans for rats
summary:
tags:
- Theses

date: "2019-06-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Skeleton registration
  focal_point: Smart

#inks:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
url_pdf: "https://drive.google.com/file/d/1EfoxiKpiZcVgnpwIcqVlDb4v1sxbwFX_/view?usp=sharing"
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Computer Tomography scans can be a great resource to not only learn the surface model but to
learn the shape and location of internal organs and bones. In this work, we will try to learn a
model for the skin and for a skeleton from rat CT scans. We will also try to achieve a kinematic
correspondence between the two models. This problem is challenging because we are trying to
learn shape space from limited data, around 10 CT scans and we start from a preliminary skin
model which is trained on 2 CT scans and 3 toy scans and a template mesh of the skeleton.
