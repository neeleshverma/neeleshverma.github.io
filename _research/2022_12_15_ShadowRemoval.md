---
title: "Shadow Removal using Diffusion Models"
collection: research
custom: 'true'
custom_remark: 'Done under Prof. Dimitris Samaras'
permalink: /research/ShadowRemoval
excerpt: 'This work explores the potential of DDPM for shadow removal tasks, where preserving hidden features is crucial. We built on a existing RePaint architecture by passing shadow information in the reverse diffusion gradually.'
date: 2022-12-15
venue: ''
paperurl: 'https://neeleshverma.github.io/reports/research/Shadow_Removal.pdf'
---

<style>

/* Style the counter cards */
.card {
<!--   box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */ -->
  padding: 16px;
<!--   text-align: center; -->
<!--   background-color: #f1f1f1; -->
}

a:link {
  text-decoration: none;
}
</style>

The efficacy of Diffusion Denoising Probabilistic Models (DDPM) has become evident in various image generation scenarios, showcasing advantages over traditional Generative Adversarial Networks (GANs). This observation prompts exploration into the potential integration of DDPM into shadow removal tasks. Motivated by this need, we present a Diffusion-based approach for shadow removal. Shadow removal, distinct from generic image generation, poses a unique challenge as the model must retain hidden shadow features while denoising, aiming for the most contextually accurate outcome. To enhance pattern generation within shadow regions, we introduce a Decay rate based method, incorporating shadow information while maintaining the contextual relevance. The decay rate, initially high, ensures a closer blending of features to the shadow region in the early diffusion steps, gradually decreasing to yield a smoother reconstruction.

View/Download Paper [here](https://neeleshverma.github.io/reports/research/Shadow_Removal.pdf)  
[Code](https://github.com/neeleshverma/Shadow_Removal)