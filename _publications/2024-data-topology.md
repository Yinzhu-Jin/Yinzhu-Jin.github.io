---
title: "Implications of data topology for deep generative models"
collection: publications
category: manuscripts
permalink: /publication/2024-data-topology
excerpt: 'Demonstrates that deep generative models struggle with data distributions possessing non-trivial topologies, highlighting limitations in data generation and interpolation.'
date: 2024-08-25
venue: 'Frontiers in Computer Science'
paperurl: 'https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1260604/full'
authors: Yinzhu Jin, Rory McDaniel, N. Joseph Tatro, Michael J. Catanzaro, Abraham D. Smith, Paul Bendich, Matthew B. Dwyer, P. Thomas Fletcher
---

**Yinzhu Jin**, Rory McDaniel, N. Joseph Tatro, Michael J. Catanzaro, Abraham D. Smith, Paul Bendich, Matthew B. Dwyer, P. Thomas Fletcher

![](/images/publications/data_topology.png)

Many deep generative models, such as variational autoencoders (VAEs) and generative adversarial networks (GANs), learn an immersion mapping from a standard normal distribution in a low-dimensional latent space into a higher-dimensional data space. As such, these mappings are only capable of producing simple data topologies, i.e., those equivalent to an immersion of Euclidean space. In this work, we demonstrate the limitations of such latent space generative models when trained on data distributions with non-trivial topologies. We do this by training these models on synthetic image datasets with known topologies (spheres, torii, etc.). We then show how this results in failures of both data generation as well as data interpolation. Next, we compare this behavior to two classes of deep generative models that in principle allow for more complex data topologies. First, we look at chart autoencoders (CAEs), which construct a smooth data manifold from multiple latent space chart mappings. Second, we explore score-based models, e.g., denoising diffusion probabilistic models, which estimate gradients of the data distribution without resorting to an explicit mapping to a latent space. Our results show that these models do demonstrate improved ability over latent space models in modeling data distributions with complex topologies, however, challenges still remain.

[Download Paper](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1260604/full)
