---
title: "“Dimensionality reduction of local structure in glassy binary mixtures” - The Journal of Chemical Physics"
subtitle: 

# Summary for listings and search engines
summary: "This study focuses on the use of dimensionality reduction techniques to assess the structural heterogeneity of glassy binary mixtures. This work is in collaboration with Daniele Coslovich and Robert L. Jack."

# Link this post with a project
#projects:

links:
  - icon: doi
    icon_pack: ai
    name: DOI
    url: https://doi.org/10.1063/5.0128265
  - name: arXiv
    icon_pack: ai
    icon: arxiv
    url: https://arxiv.org/abs/2211.01904
  - icon: link
    icon_pack: fas
    name: Code
    url: https://www.jorisparet.com/partycls
  - icon: zenodo
    icon_pack: ai
    name: Dataset
    url: https://doi.org/10.5281/zenodo.7108317
    
# Date published
date: '2022-10-24T00:00:00Z'

# Date updated
lastmod: '2022-10-24T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ''
  placement: 2
  preview_only: false

authors:

tags:
  - Physics
  - Machine Learning
  - Molecular Dynamics

categories:

---

# Authors
- Daniele Coslovich
- Robert L. Jack
- Joris Paret

# Abstract

We consider unsupervised learning methods for characterizing the disordered microscopic structure of supercooled liquids and glasses. Specifically, we perform dimensionality reduction of smooth structural descriptors that describe radial and bond-orientational correlations and assess the ability of the method to grasp the essential structural features of glassy binary mixtures. In several cases, a few collective variables account for the bulk of the structural fluctuations within the first coordination shell and also display a clear connection with the fluctuations of particle mobility. Fine-grained descriptors that characterize the radial dependence of bond-orientational order better capture the structural fluctuations relevant for particle mobility but are also more difficult to parameterize and to interpret. We also find that principal component analysis of bond-orientational order parameters provides identical results to neural network autoencoders while having the advantage of being easily interpretable. Overall, our results indicate that glassy binary mixtures have a broad spectrum of structural features. In the temperature range we investigate, some mixtures display well-defined locally favored structures, which are reflected in bimodal distributions of the structural variables identified by dimensionality reduction.

# Article and data availability

This paper is published [The Journal of Chemical Physics](https://doi.org/10.1063/5.0128265) and is also available on [arXiv](https://arxiv.org/abs/2211.01904). The computation of descriptors and most of the dimensionality reduction analysis were performed using the [partycls](https://www.jorisparet.com/partycls) package. Data analysis has been carried out using a reproducible workflow, deposited in the Zenodo [public repository](https://doi.org/10.5281/zenodo.7108317).