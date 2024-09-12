---
abstract:In this thesis, we propose several methods to address data issues related to the Beamm project. The core of this project is to develop a tax-benefit microsimulation model for Belgium accessible online, requiring intensive data handling. Our challenges consist in creating a unified data set containing variables from different surveys and developing a completely synthetic database for the online development of the Beamm platform.
In Chapters 2 and 3, we introduce various approaches to perform statistical matching using machine learning techniques such as Kernel Canonical Correlation Analysis (KCCA), Super-Organizing Map (Super-OM), Autoencoder-Canonical Correlation Analysis (A-CCA) and Multi-output Multilayer Perceptron (MMLP). We include sampling weights in all the methodologies. Moreover, we present a two-step approach to handle data sets containing both categorical and continuous variables, and to address inconsistencies between categorical variables. We have seen that the proposed methodologies can be competitive, especially with KCCA and A-CCA, which combine the distinct advantages of the results obtained with both hot-deck and regression-based methods.
In Chapter 4, we employ a range of data generation approaches utilizing various advancements in the Wasserstein Generative Adversarial Network (WGAN) literature. Our algorithms have been adjusted to account for sampling weights, and a new metric based on Support Vector Data Description (SVDD) has been introduced to assess the quality of the generated data. This measure indicates the relative difference between two radii, making it useful for practitioners who have access to a percentage of deviation of the synthetic data compared to the original data. Through our experiments, it became evident that methods employing gradient penalty and sampling weights produced the most favorable outcomes across a spectrum of metrics.
authors:
- admin
- Cédric Heuchenne (Advisor)
date: "2024-09-11"
doi: ""
featured: false
image:
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
publication: ''
publication_short: ""
publication_types:
- "0"
publishDate: "2024-09-11"
slides: ""
summary: ""
tags:
- Wavelet
title: Thesis, Statistical matching and data generation
url_pdf: 
---

