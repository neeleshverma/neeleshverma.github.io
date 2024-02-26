---
title: "Imitating Expert Behaviour with Optimal Transport Distances"
collection: research
custom: 'true'
custom_remark: 'Done as a research project under Prof. Michael Ryoo'
permalink: /research/RLOTDistance
excerpt: 'In this report, we introduce an algorithm for reward annotation in offline Reinforcement Learning (RL) employing the Optimal Transport (OT) strategy based on Wasserstein distance. Leveraging OT, the algorithm calculates optimal alignments between unlabeled trajectories and expert demonstrations, treating the similarity measure as a reward label.'
date: 2023-05-15
venue: ''
paperurl: 'https://neeleshverma.github.io/reports/research/RL_OT_Distance.pdf'
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

Offline Reinforcement Learning (RL) confronts the challenge of requiring reward annotation in the dataset, a process that is often arduous and time-consuming. This report introduces an innovative algorithm aimed at addressing this hurdle by employing the Optimal Transport strategy for reward annotation in offline RL. Leveraging optimal transport, the algorithm calculates an optimal alignment between unlabeled trajectories and expert demonstrations, demonstrating superior performance in certain environments and exceptional efficacy in others. The exploration of Optimal Transport within this project revolves around assuming the availability of at least one expert demonstration. By finding optimal alignments between expert trajectories and unlabeled trajectories, the similarity measure between states becomes a reward label, facilitating the annotation of trajectories for subsequent use in any offline RL algorithm.

 The efficiency of our algorithm is intricately tied to the estimation of the Wasserstein distance through Sinkhorn divergence. In this paper, we worked with Imitation Q-Learning (IQL), although the framework accommodates the use of any other algorithm.

Paper [here](https://neeleshverma.github.io/reports/research/RL_OT_Distance.pdf)  
Code [here](https://github.com/neeleshverma/Offline-RL-RewardLabelling)