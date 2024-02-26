---
title: "Extraction of Facial Features from Speech"
collection: research
custom: 'true'
custom_remark: "A class project for CS 753 (Automatic Speech Recognition), Fall '19"
permalink: /projects/Speech2Face
excerpt: "The project aimed to infer a person's appearance from their voice using a deep neural network trained on YouTube videos. The network encodes speech into a face feature and then decodes it into a canonical face image."
date: 2019-12-15
venue: 'NA'
paperurl: 'https://neeleshverma.github.io/reports/projects/Facial_Feat_Extract.pdf'
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

In this project, the primary objective was to explore the ability to infer visual information about a person's appearance based on their speech patterns. To achieve this, we developed and trained a deep neural network using a substantial dataset comprised of natural YouTube videos featuring individuals speaking. The training process involved the model learning intricate voice-face correlations, and subsequently, we employed the trained model for voice recognition to assess its overall efficiency. Notably, our training approach embraced a self-supervised methodology, capitalizing on the inherent co-occurrence of faces and speech in online videos without explicit attribute modeling. 

The pipeline consisted of two integral components: 1) a voice encoder, adept at processing complex speech spectrograms and predicting a low-dimensional face feature corresponding to the associated face; and 2) a face decoder, which took the predicted face feature as input and generated an image of the face in a standardized form, presenting a frontal-facing perspective with a neutral expression.  

Project Report [here](https://neeleshverma.github.io/reports/projects/Facial_Feat_Extract.pdf)
Code [here](https://github.com/neeleshverma/Speech2Face)