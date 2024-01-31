# Biases in parasite richness estimates arising from coinfection
dynamics
2024-01-15

## Can coinfection dynamics bias population estimates of parasite richness?

-   The short answer: yes.

## Are interactions among parasites, viruses, and bacteria common?

-   The short answer: we don’t know
-   Interactions can be inferred with experimental infections, parasite
    removal, and longitudinal studies of infection
-   These haven’t been done very often
-   Amy Sweeny will change this, we hope

## Observation: Richness estimates assume no parasite interaction

![Conceptual diagram of richness estimates becoming biased when
parasites interact](synbias%20concept.png)

## Research Question

What are we missing when we estimate parasite or viral richness without
accounting for coinfection dynamics?

## Approach: Individual-based modeling

SI model with pairwise interactions and no demography

<img src="model%20diagram%201.png"
data-fig-alt="Conceptual diagram of two strains spreading in a bat population" />

## Approach: Parameter space explored

<img src="parameters%20coinfection.png"
data-fig-alt="Illustrations of number of strains, competitive:facilitative ratio, interaction strength, and proportion of population sampled" />

## Approach: What a single simulation looks like

![](synbias-slides.markdown_github_files/figure-markdown_github/single%20sim-1.png)

## Does greater parasite richness “smooth out” effects of interaction on bias?

![](synbias-slides.markdown_github_files/figure-markdown_github/strain%20number-1.png)

## Does the strength of interactions matter?

![](synbias-slides.markdown_github_files/figure-markdown_github/interaction%20strength-1.png)

## What about the proportion of the population sampled?

You’d think this would be the most important factor. However…

![](synbias-slides.markdown_github_files/figure-markdown_github/sample%20prop-1.png)

## Interactions between strains are more important than % sampled

![](synbias-slides.markdown_github_files/figure-markdown_github/sample%20prop%20cf%20ratio-1.png)

## Up Next

-   More simulations, this time with a lower baseline transmission rate

-   A search for any empirical data about C:F ratio and interaction
    strength in microbial communities
