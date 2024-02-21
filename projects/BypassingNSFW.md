---
title: "Bypassing NSFW Gatekeepers"
collection: research
custom: 'true'
custom_remark: 'A class project for CSE 509, Fall '23''
permalink: /research/CrackFusion
excerpt: 'The paper introduces a novel approach using diffusion models to create accurate crack segmentation maps by leveraging original image data during reverse diffusion. A "RefineNet" model then ensures the generated maps at each timestep align topologically with actual crack structures.'
date: 2023-12-15
venue: ''
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

This project explores and exploits the content moderation filters on social media platforms. The study delves deep into the vulnerabilities of these filters, employing a systematic "black-box" attack approach. We unveil an innovative technique harnessing Grad-CAM heatmaps, which highlight key pixels crucial for image classification. Armed with this knowledge, we strategically inject calculated noise into these areas, crafting "adversarial attacks" that bypass the filters' defenses. By systematically testing the attack on popular social media platforms - Bumble and Reddit, we expose the potential for misuse and raise critical questions about the effectiveness and reliability of content moderation systems.