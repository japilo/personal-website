---
title: epizootic
summary: An R package for spatially explicit population models of disease transmission in wildlife
authors: [admin]
tags: [disease ecology, coinfection, process-explicit modeling, theory]
categories: []
date: '2024-01-31T00:00:00Z'
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
---

## epizootic
## An R package for process-explicit models of wildlife disease
July Pilowsky

---

## What is machine learning?

![](/epizootic-slides/machine_learning.png)

---

## What is a process-explicit model?

![](/epizootic-slides/pattern_process.png)

---

## What do you need to make one?

- Theory about how the study system works
- This is all you really need, because process-explicit models can be data-free

--- 

## OK, July, but not all models can or should be data-free

{{% fragment %}} -   Data on processes (such as nitrogen fixation rate or replication fidelity) {{% /fragment %}}
{{% fragment %}} -   Data on drivers (such as temperature or % impervious surface) {{% /fragment %}}
{{% fragment %}} -   Observed patterns that can be compared to model outputs for validation {{% /fragment %}}