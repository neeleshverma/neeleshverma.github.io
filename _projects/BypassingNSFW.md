---
title: "Bypassing NSFW Gatekeepers"
collection: research
custom: 'true'
custom_remark: "A class project for CSE 509, Fall '23"
permalink: /projects/BypassingNSFW
excerpt: 'This project delves into the vulnerabilities of NSFW detectors on social media platforms. We employed a systematic black-box attack methodology, leveraging Grad-CAM-generated heatmaps, the study exposes weaknesses in existing detectors, offering insights into the robustness of content moderation systems.'
date: 2023-12-15
venue: 'NA'
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

This project explores and exploits the content moderation filters on social media platforms. The study delves deep into the vulnerabilities of these filters, employing a systematic "black-box" attack approach. We unveil an innovative technique harnessing Grad-CAM heatmaps, which highlight key pixels crucial for image classification as NSFW or not. Armed with this knowledge, we strategically inject calculated noise into these areas, crafting "adversarial attacks" that bypass the filters' defenses. By systematically testing the attack on popular social media platforms - Bumble and Reddit, we expose the potential for misuse and raise critical questions about the effectiveness and reliability of content moderation systems.