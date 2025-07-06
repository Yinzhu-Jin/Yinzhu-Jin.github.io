---
title: "Point-Based Shape Representation Generation with a Correspondence-Preserving Diffusion Model"
collection: publications
category: conferences
permalink: /publication/2025-correspondence-preserving
excerpt: 'Presents a diffusion model that generates point-based shape representations while preserving anatomical correspondences, addressing limitations in traditional deep learning methods.'
date: 2025-05-26
venue: 'Medical Imaging with Deep Learning'
paperurl: 'https://openreview.net/forum?id=qiSVJGFAar'
authors: Shen Zhu, Yinzhu Jin, Ifrah Zawar, Tom Fletcher
---

Shen Zhu, **Yinzhu Jin**, Ifrah Zawar, Tom Fletcher

![](/images/publications/correspondence.png)

We propose a diffusion model designed to generate point-based shape representations with correspondences. Traditional statistical shape models have considered point correspondences extensively, but current deep learning methods do not take them into account, focusing on unordered point clouds instead. Current deep generative models for point clouds do not address generating shapes with point correspondences between generated shapes. This work aims to formulate a diffusion model that is capable of generating realistic point-based shape representations, which preserve point correspondences that are present in the training data. Using shape representation data with correspondences derived from Open Access Series of Imaging Studies 3 (OASIS-3), we demonstrate that our correspondence-preserving model effectively generates point-based hippocampal shape representations that are highly realistic compared to existing methods. We further demonstrate the applications of our generative model by downstream tasks, such as conditional generation of healthy and AD subjects and predicting morphological changes of disease progression by counterfactual generation.

[Download Paper](https://openreview.net/forum?id=qiSVJGFAar)
