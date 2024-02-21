---
title: "Shadow Removal"
collection: research
custom: 'true'
custom_remark: 'Done under Prof. Dimitris Samaras'
permalink: /research/ShadowRemoval
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2022-11-01
venue: 'Journal 1'
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