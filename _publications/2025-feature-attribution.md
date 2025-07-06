---
title: "Feature Attribution for Deep Learning Models through Total Variance Decomposition"
collection: publications
category: conferences
permalink: /publication/2025-feature-attribution
excerpt: 'Introduces a statistically grounded method for feature attribution by decomposing model decision variance, enhancing interpretability in deep learning models.'
date: 2025-06-04
venue: 'Medical Imaging with Deep Learning'
paperurl: 'https://openreview.net/pdf?id=R4lRVjL4KX'
authors: Yinzhu Jin, Coauthor A, Coauthor B
---

![](/images/publications/feature_attribution.PNG)

This paper introduces a new approach to feature attribution for deep learning models, quantifying the importance of specific features in model decisions. By decomposing the total variance of model decisions into explained and unexplained fractions, conditioned on the target feature, we define the feature attribution score as the proportion of explained variance. This method offers a solid statistical foundation and normalized quantitative results. When ample data is available, we compute the score directly from test data. For scarce data, we use constrained sampling with generative diffusion models to represent the conditional distribution at a given feature value. We demonstrate the method’s effectiveness on both a synthetic image dataset with known ground truth and OASIS-3 brain MRIs.
