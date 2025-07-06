---
title: "MedIL: Implicit Latent Spaces for Generating Heterogeneous Medical Images at Arbitrary Resolutions"
collection: publications
category: conferences
permalink: /publication/2025-medil
excerpt: 'Introduces MedIL, an autoencoder utilizing implicit neural representations to generate medical images at arbitrary resolutions, preserving fine anatomical details without resampling.'
date: 2025-04-12
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2504.09322'
authors: Tyler Spears, Shen Zhu, Yinzhu Jin, Aman Shrivastava, P. Thomas Fletcher
---

Tyler Spears, Shen Zhu, **Yinzhu Jin**, Aman Shrivastava, P. Thomas Fletcher

![](/images/publications/medil.PNG)

In this work, we introduce MedIL, a first-of-its-kind autoencoder built for encoding medical images with heterogeneous sizes and resolutions for image generation. Medical images are often large and heterogeneous, where fine details are of vital clinical importance. Image properties change drastically when considering acquisition equipment, patient demographics, and pathology, making realistic medical image generation challenging. Recent work in latent diffusion models (LDMs) has shown success in generating images resampled to a fixed-size. However, this is a narrow subset of the resolutions native to image acquisition, and resampling discards fine anatomical details. MedIL utilizes implicit neural representations to treat images as continuous signals, where encoding and decoding can be performed at arbitrary resolutions without prior resampling. We quantitatively and qualitatively show how MedIL compresses and preserves clinically-relevant features over large multi-site, multi-resolution datasets of both T1w brain MRIs and lung CTs. We further demonstrate how MedIL can influence the quality of images generated with a diffusion model, and discuss how MedIL can enhance generative models to resemble raw clinical acquisitions.

[Download Paper](https://arxiv.org/abs/2504.09322)
