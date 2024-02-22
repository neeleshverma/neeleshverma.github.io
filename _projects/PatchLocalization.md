---
title: "Frequency based Adversarial Patch Localization"
collection: research
custom: 'true'
custom_remark: "Work done as an Intern at SRI International, Summer '23"
permalink: /projects/PatchLocalization
excerpt: 'This study introduces a frequency-based adversarial patch detection method using SAM segmentation and SVM classification on image segments. Through independent analyses of DFT, FFT, and entropy, our approach proves effective in reliably identifying adversarial patches, offering promising advancements in image security against adversarial attacks.'
date: 2023-08-15
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

In this study, we present a novel approach for detecting adversarial patches in images through a frequency-based analysis. Leveraging the Segment Anything Model (SAM), we initially segment the images, creating distinct regions of interest. Subsequently, we employ a single class Support Vector Machine (SVM) to train on these segments, distinguishing adversarial patches from the natural ones. Our investigation delves into various frequency components, including Discrete Fourier Transform (DFT), Fast Fourier Transform (FFT), and entropy, each operating independently. The results demonstrate the effectiveness of our method in robustly identifying adversarial patches, showcasing the potential of frequency-based analysis for enhancing image security in the realm of adversarial attacks. Additionally, we inpainted the adversarial patch segments using Stable Diffusion thus decreasing the Attack Success Rate (ASR).