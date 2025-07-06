---
title: "Measuring Feature Dependency of Neural Networks by Collapsing Feature Dimensions in The Data Manifold"
collection: publications
category: conferences
permalink: /publication/2024-collapsing-feature
excerpt: 'Introduces a technique to assess neural network feature dependency by collapsing specific feature dimensions on the data manifold and observing performance degradation.'
date: 2024-05-27
venue: 'International Symposium on Biomedical Imaging'
paperurl: 'https://arxiv.org/abs/2404.12341'
authors: Yinzhu Jin, Matthew B. Dwyer, P. Thomas Fletcher
---

**Yinzhu Jin**, Matthew B. Dwyer, P. Thomas Fletcher

![](/images/publications/collapse-feature.png)

This paper introduces a new technique to measure the feature dependency of neural network models. The motivation is to better understand a model by querying whether it is using information from human-understandable features, e.g., anatomical shape, volume, or image texture. Our method is based on the principle that if a model is dependent on a feature, then removal of that feature should significantly harm its performance. A targeted feature is "removed" by collapsing the dimension in the data distribution that corresponds to that feature. We perform this by moving data points along the feature dimension to a baseline feature value while staying on the data manifold, as estimated by a deep generative model. Then we observe how the model's performance changes on the modified test data set, with the target feature dimension removed. We test our method on deep neural network models trained on synthetic image data with known ground truth, an Alzheimer's disease prediction task using MRI and hippocampus segmentations from the OASIS-3 dataset, and a cell nuclei classification task using the Lizard dataset.

[Download Paper](https://arxiv.org/abs/2404.12341)
