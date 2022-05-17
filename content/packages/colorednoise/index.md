---
title: colorednoise
summary: The colorednoise package simulates colored noise as well as structured and unstructured population models with colored noise.
tags:
date: '2020-08-05T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Star
    url: https://github.com/japilo/colorednoise
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Temporally autocorrelated populations are correlated in their vital rates (growth, death, etc.) from year to year. It is very common for populations, whether they be bacteria, plants, or humans, to be temporally autocorrelated. This poses a challenge for stochastic population modeling, because a temporally correlated population will behave differently from an uncorrelated one. This package provides tools for simulating populations with white noise (no temporal autocorrelation), red noise (positive temporal autocorrelation), and blue noise (negative temporal autocorrelation). The algebraic formulation for autocorrelated noise comes from Ruokolainen et al. (2009) <doi:10.1016/j.tree.2009.04.009>. Models for unstructured populations and for structured populations (matrix models) are available.
