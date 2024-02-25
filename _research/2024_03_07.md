---
title: "CrackFusion"
collection: research
custom: 'true'
custom_remark: 'Ongoing (To be submitted to ECCV 2024)'
permalink: /research/CrackFusion
excerpt: 'The paper introduces a novel approach using diffusion models to create accurate crack segmentation maps by leveraging original image data during reverse diffusion. A "RefineNet" model then ensures the generated maps at each timestep align topologically with actual crack structures.'
date: 2024-03-07
venue: 'ECCV 2024'
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

In this paper, we utilized Diffusion Models to address the challenge of crack segmentation. Traditional Diffusion-based segmentation methods have struggled to effectively capture the continuous nature of cracks. Previous models designed for crack segmentation exhibited suboptimal performance when faced with cracks of varying thickness. To overcome these limitations, we introduced CrackFusion, a novel Diffusion-based Crack Segmentation approach. The segmentation mask is generated through a reverse diffusion process, incorporating information from the original image. Additionally, to enhance the precision of crack delineation throughout the reverse diffusion steps, we introduced a dedicated U-Net-like model, RefineNet. This auxiliary model plays a crucial role in preserving the topological structure of the cracks during the refinement process.

Our proposed CrackFusion methodology represents a significant advancement in crack segmentation, overcoming challenges posed by the inadequacies of existing Diffusion-based approaches. By integrating reverse diffusion and a specialized refinement model, we aim to achieve more accurate and robust crack segmentation, particularly in scenarios involving varying crack thicknesses.


Paper to be released soon.