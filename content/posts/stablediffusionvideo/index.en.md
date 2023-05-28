---
weight: 4
title: "Stable Diffusion custom workflow for rendering video"
date: 2023-04-03T16:29:41+08:00
lastmod: 2023-03-03T16:29:41+08:00
draft: false
author: "Jorge Vega"
authorLink: "jvega.xyz"
description: "Stable Diffusion custom workflow for rendering video"
images: []
resources:
- name: "featured-image"
  src: "featured-image.gif"

tags: ["machine learning"]
categories: ["projects"]

lightgallery: true

math:
  enable: true
---

Developed a simple python script that leverages stable diffusion models to enhance video quality by post rendering a stylized frame. I discovered that by using Stable diffusion models and simple shadering I can improve rendering and post styling. This might be something that is getting interesting lately. By using gradio and stable diffusion 1.5 I rendered some stylized images.

Afterwards, i thought about integrating frame interpolation into the workflow and to add custom color correction to prevent flickering. By automatically inserting these extra frames, I achieved smoother and more natural motion in the videos plus keeping better overall structural stability.

The results are not incredible but promising.
