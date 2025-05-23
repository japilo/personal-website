---
title: Biases in parasite richness estimates arising from coinfection dynamics
summary: We present a likely source of bias in estimates of parasite richness - emergent properties arising from interactions between parasites. In the absence of good coinfection data, we provide a theoretical exploration.
authors: [admin]
tags: [disease ecology, coinfection, process-explicit modeling, theory]
categories: []
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  highlight_style: dracula
css: /synbias-slides/slides-style.css
---

## Biases in parasite richness estimates arising from coinfection dynamics
July Pilowsky, Amy Sweeny, Greg Albery, Barbara Han

---

## Can coinfection dynamics bias population estimates of parasite richness?

-   The short answer: yes.

---

## Are interactions among parasites, viruses, and bacteria common?

-   The short answer: we don’t know
-   Interactions can be inferred with experimental infections, parasite removal, and longitudinal studies of infection
-   These haven’t been done very often
-   Amy Sweeny will change this, we hope

---

![Conceptual diagram of richness estimates becoming biased when
parasites interact](/synbias-slides/synbias%20concept.png)

---

## Research Question

What are we missing when we estimate parasite or viral richness without
accounting for coinfection dynamics?

---

## Approach: Individual-based modeling

SI model with pairwise interactions and no demography

<img src="/synbias-slides/model%20diagram%201.png"
data-fig-alt="Conceptual diagram of two strains spreading in a bat population" />

---

## Approach: Parameter space explored

<img src="/synbias-slides/parameters%20coinfection.png"
data-fig-alt="Illustrations of number of strains, competitive:facilitative ratio, interaction strength, and proportion of population sampled" />

---

## Approach: What a single simulation looks like

![](/synbias-slides/synbias-slides.markdown_github_files/figure-markdown_github/single%20sim-1.png)

---

## Does high parasite richness “smooth out” interaction?

![](/synbias-slides/synbias-slides.markdown_github_files/figure-markdown_github/strain%20number-1.png)

---

## Does the strength of interactions matter?

![](/synbias-slides/synbias-slides.markdown_github_files/figure-markdown_github/interaction%20strength-1.png)

---

## proportion of the population sampled

![](/synbias-slides/synbias-slides.markdown_github_files/figure-markdown_github/sample%20prop-1.png)

---

## Interactions between strains are more important

![](/synbias-slides/synbias-slides.markdown_github_files/figure-markdown_github/sample%20prop%20cf%20ratio-1.png)

---

## Up Next

-   More simulations, this time with a lower baseline transmission rate

-   A search for any empirical data about C:F ratio and interaction strength in microbial communities
