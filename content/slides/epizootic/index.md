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
css: /epizootic-slides/slides-style.css
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

---

## How do these models apply to disease ecology?

![](/epizootic-slides/disease_processes.png)

---

## Introducing epizootic

[![](/post/r-package-logo/featured.png)](https://github.com/viralemergence/epizootic)

---

## The structure of epizootic

![](/epizootic-slides/epizootic_structure.png)

---

## Case study: house finch conjunctivitis

![Image credit: Kerry Hargrove](/epizootic-slides/conjunctivitis.jpeg)

---

## epizootic in practice

![](/epizootic-slides/mgsim_structure.png)

---

## epizootic in practice

Summer 1940             |  Winter 1993
:-------------------------:|:-------------------------:
![](/epizootic-slides/initial_abundance.png)  |  ![](/epizootic-slides/winter1993.png)

---

## Processes and drivers considered for house finch conjunctivitis

{{% fragment %}} -   Land use change (urbanization) {{% /fragment %}}
{{% fragment %}} -   Climate change {{% /fragment %}}
{{% fragment %}} -   Density-dependent dispersal {{% /fragment %}}
{{% fragment %}} -   Local extirpation by the disease {{% /fragment %}}

---

## What questions could we answer using epizootic?

{{% fragment %}} -   Does urbanization facilitate the spread of wildlife disease? {{% /fragment %}}
{{% fragment %}} -   Does topography/elevation slow the spread of wildlife disease? {{% /fragment %}}
{{% fragment %}} -   Does hunting change the dynamics of wildlife disease? {{% /fragment %}}
{{% fragment %}} -   Suggest some I haven't thought of yet! {{% /fragment %}}

---

## Roadmap for epizootic

{{% fragment %}} -   Complete the house finch conjunctivitis case study {{% /fragment %}}
{{% fragment %}} -   Create a tutorial so it is easier for other people to use {{% /fragment %}}
{{% fragment %}} -   Add functionality for dispersal that differs by season and for the inclusion of hunting (?) {{% /fragment %}}
{{% fragment %}} -   Case study in vector-borne system (?) {{% /fragment %}}