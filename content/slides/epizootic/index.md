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

## Choosing a study system

I needed to choose a study system on which to test out epizootic based on these criteria:

{{% fragment %}} -   Verena-scale problem (continental) {{% /fragment %}}
{{% fragment %}} -   Enough data to parameterize and independently validate the model {{% /fragment %}}
{{% fragment %}} -   Enough theory about the system that we know which processes to include {{% /fragment %}}

---

## Case study: house finch conjunctivitis

![Image credit: Kerry Hargrove](/epizootic-slides/conjunctivitis.jpeg)

---

## epizootic in practice

![](/epizootic-slides/mgsim_structure.png)

---

## epizootic in practice

Processes included in the model:

{{% fragment %}} -   Transmission dynamics (discrete time SIRI models, parameters differing by season and life cycle stage) {{% /fragment %}}
{{% fragment %}} -   Density-dependent dispersal, parameters differing by life cycle stage {{% /fragment %}}
{{% fragment %}} -   Density-dependent fecundity and mortality, with mortality differing by infection status {{% /fragment %}}

---

## epizootic in practice

Drivers included in the model:

{{% fragment %}} -   Environmental change (climate and land use) {{% /fragment %}}
{{% fragment %}} -   Invasion dynamics (introduction of house finches to NY) {{% /fragment %}}
{{% fragment %}} -   Initial spillover event from poultry in 1994 {{% /fragment %}}

---

## Parameterization for epizootic

{{% fragment %}} -   House finch demography {{% /fragment %}}
{{% fragment %}} -   House finch banding survey data on dispersal {{% /fragment %}}
{{% fragment %}} -   Transmission, recovery, and partial immunity for the disease {{% /fragment %}}
{{% fragment %}} -   Spatially explicit breeding season length (inferred from eastern bluebird data) {{% /fragment %}}
{{% fragment %}} -   Historical climate data {{% /fragment %}}
{{% fragment %}} -   Historical land use data {{% /fragment %}}

---

## Validation for epizootic

{{% fragment %}} -   Presence of house finches in Washington DC in 1994 {{% /fragment %}}
{{% fragment %}} -   Date of arrival of house finch conjunctivitis in Northeast regions {{% /fragment %}}
{{% fragment %}} -   Spatiotemporal point prevalence of conjunctivitis {{% /fragment %}}
{{% fragment %}} -   Rate of change in house finch abundance {{% /fragment %}}
{{% fragment %}} -   Date of arrival of house finches east of the Rockies {{% /fragment %}}
{{% fragment %}} -   Presences and true absences of house finches in North America {{% /fragment %}}

---

## Validation for epizootic

![](/epizootic-slides/posteriors.png)

---

## epizootic and you

How can epizootic integrate with the research that you do at Verena?

---

## epizootic and you

![](/epizootic-slides/epizootic_structure.png)

---

## epizootic and you

![](/epizootic-slides/generators.png)

---

## epizootic and you

I believe that process-explicit modeling is an excellent and rigorous way to model ecological processes at multiple scales. How can it help **you**? Let's discuss!