---
weight: 4
title: "Automata Shaders"
draft: false
author: "Jorge Vega"
authorLink: "jvega.xyz"
description: "Automata Shader test"
images: []
resources:
- name: "featured-image"
  src: "featured-image.gif"

tags: ["GLSL"]
categories: ["projects"]

lightgallery: true

math:
  enable: true
---


A project I made few years ago while testing and learning GLSL shading language and the graphics pipeline. Given simple rules automata follow complex patters. In this example I assigned a weight function for each automata which computed the best location in the next move based on distance to other automata and "fuel" locations. Mixed with a vornoi style noise rules, this creates emerging biological patterns similar to fungi structures.


