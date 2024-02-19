---
title: "CrackFusion"
collection: research
permalink: /research/CrackFusion
excerpt: 'In this paper, we propose CrackFusion, a Diffusion Model for Crack Segmentation, that can capture thick cracks to very fine ones.'
date: 2024-03-07
venue: 'Ongoing (To be submitted to ECCV '24)'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Neelesh Verma, Haibin Ling'
---

In my research, I utilized Diffusion Models to address the challenge of crack segmentation. Traditional Diffusion-based segmentation methods have struggled to effectively capture the continuous nature of cracks. Previous models designed for crack segmentation exhibited suboptimal performance when faced with cracks of varying thickness. To overcome these limitations, we introduced CrackFusion, a novel Diffusion-based Crack Segmentation approach. The segmentation mask is generated through a reverse diffusion process, incorporating information from the original image. Additionally, to enhance the precision of crack delineation throughout the reverse diffusion steps, we introduced a dedicated U-Net-like model. This auxiliary model plays a crucial role in preserving the topological structure of the cracks during the refinement process.

Our proposed CrackFusion methodology represents a significant advancement in crack segmentation, overcoming challenges posed by the inadequacies of existing Diffusion-based approaches. By integrating reverse diffusion and a specialized refinement model, we aim to achieve more accurate and robust crack segmentation, particularly in scenarios involving varying crack thicknesses.


Paper to be released soon.
<!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->