---
title: "Speech Denoising"
collection: research
custom: 'true'
custom_remark: 'Bachelor Thesis Project (BTP) under Prof. P Balamurugan'
permalink: /research/SpeechDeoising
excerpt: 'This work proposes an end-to-end deep learning methodology for speech enhancement, employing a fully convolutional neural network (FCN) guided by perceptual feature losses for generating clean audio from noisy inputs. The approach emphasizes the training of the Denoising network to preserve intricate details at multiple layers through another network, FeatureLoss Net.'
date: 2024-05-15
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


<div class="card" style="display: flex; text-align: center;">

  <div style="width: 50%;">
    <p style="font-size: smaller;">Noisy Audio</p>
    <audio controls style="width: 100%;">
      <source src="/mp3files/noisy1.mp4" type="audio/mp3">
      Your browser does not support the audio tag.
    </audio>
  </div>

  <div style="width: 50%;">
    <p style="font-size: smaller;">Clean Audio</p>
    <audio controls style="width: 100%;">
      <source src="/mp3files/clean1.mp4" type="audio/mp3">
      Your browser does not support the audio tag.
    </audio>
  </div>

</div>

<br>

In this report, we introduce a end-to-end deep learning approach for speech enhancement, leveraging a fully convolutional neural network (FCN) to generate clean audio from noisy inputs. The training process incorporates a Feature Loss network, tasked with learning feature embeddings for audio signals. By guiding our Denoising network through perceptual losses derived from differences in feature embeddings, particularly from established sources, we evaluate our model's performance through a unique lens termed "Perceptual Feature Losses." Our findings affirm the superiority of this approach over existing techniques, validated through perceptual experiments involving human listeners, suggesting a promising avenue for speech quality enhancement and noise reduction.

At the heart of our approach lies the training of the Denoising network, where exposure to noisy audio inputs allows it to learn over time through evaluating perceptual feature losses against corresponding clean audio. This mechanism ensures the generation of representations closely mirroring clean audio signals at various processing stages.