---
title: "Swin Transformer Based Crack Detection"
collection: completedpublication
permalink: /research/CrackSwin-T
excerpt: 'In this paper, we proposes CrackSwinT, a novel crack detection approach, which employs the Shifted window Transformer (Swin-T) architecture, integrating Swin attention blocks and skip connections within encoders and decoders for enhanced efficiency and stability.'
date: 2024-01-05
venue: 'IEEE TITS'
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

The paper introduces a new crack detection approach, CrackSwinT, leveraging the Shifted window Transformer (Swin-T) architecture for its effective multi-scale representation. CrackSwinT enhances the previous state-of-the-art CrackFormer by incorporating Swin attention blocks for increased efficiency, introducing skip connections within encoders and decoders to enhance information flow, and utilizing focal loss to handle imbalances in crack and non-crack pixel samples. Extensive experiments on three crack detection benchmarks, including CFD, Crack200, and the enhanced Crack500fix, demonstrate CrackSwinT's superior performance over previous state-of-the-art methods, achieving nearly 5% improvement in optimal dataset scale (ODS) and optimal image scale (OIS) scores on Crack500fix.