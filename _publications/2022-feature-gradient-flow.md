---
title: "Feature gradient flow for interpreting deep neural networks in head and neck cancer prediction"
collection: publications
category: conferences
permalink: /publication/2022-feature-gradient-flow
excerpt: 'Presents "feature gradient flow", a method that aligns interpretable features with model gradient flows to elucidate decision-making in cancer prediction models.'
date: 2022-03-28
venue: 'International Symposium on Biomedical Imaging'
paperurl: 'https://arxiv.org/abs/2307.13061'
authors: Yinzhu Jin, Jonathan C. Garneau, P. Thomas Fletcher
---

**Yinzhu Jin**, Jonathan C. Garneau, P. Thomas Fletcher

![](/images/publications/gradient-flow.png)

This paper introduces feature gradient flow, a new technique for interpreting deep learning models in terms of features that are understandable to humans. The gradient flow of a model locally defines nonlinear coordinates in the input data space representing the information the model is using to make its decisions. Our idea is to measure the agreement of interpretable features with the gradient flow of a model. To then evaluate the importance of a particular feature to the model, we compare that feature's gradient flow measure versus that of a baseline noise feature. We then develop a technique for training neural networks to be more interpretable by adding a regularization term to the loss function that encourages the model gradients to align with those of chosen interpretable features. We test our method in a convolutional neural network prediction of distant metastasis of head and neck cancer from a computed tomography dataset from the Cancer Imaging Archive.

[Download Paper](https://arxiv.org/abs/2307.13061)
