---
date: 2025-07-01T00:00:00+01:00
draft: false
title: ""
jobTitle: "Uncertainty Quantification for Motor Imagery BCI - Machine Learning vs. Deep Learning"
location: "Joris Suurmeijer, Ivo Pascal de Jong, Matias Valdenegro-Toro, Andreea Ioana Sburlea"
company: "Decoding the Brain Time Series @ MLSP"
duration: "2025"
companyLogo: ""

---
*Abstract*: Brain-computer interfaces (BCIs) turn brain signals into functionally useful output, but they are not always accurate. A good Machine Learning classifier should be able to indicate how confident it is about a given classification, by giving a probability for its classification. Standard classifiers for Motor Imagery BCIs do give such probabilities, but research on uncertainty quantification has been limited to Deep Learning. We compare the uncertainty quantification ability of established BCI classifiers using Common Spatial Patterns (CSP-LDA) and Riemannian Geometry (MDRM) to specialized methods in Deep Learning (Deep Ensembles and Direct Uncertainty Quantification) as well as standard Convolutional Neural Networks (CNNs).
We found that the overconfidence typically seen in Deep Learning is not a problem in CSP-LDA and MDRM. We found that MDRM is underconfident, which we solved by adding Temperature Scaling (MDRM-T). CSP-LDA and MDRM-T give the best uncertainty estimates, but Deep Ensembles and standard CNNs give the best classifications. We show that all models are able to separate between easy and difficult estimates, so that we can increase the accuracy of a Motor Imagery BCI by rejecting samples that are ambiguous.

[Open Access Link](https://doi.org/10.48550/arXiv.2507.07511)