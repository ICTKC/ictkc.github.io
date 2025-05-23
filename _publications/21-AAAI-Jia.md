---
title: "Flexible Non-Autoregressive Extractive Summarization with Threshold: How to Extract a Non-Fixed Number of Summary Sentences"
collection: publications
permalink: /publication/AAAI-21-Jia
excerpt: ''
date: 2021-05-18
venue: 'AAAI (CCF-A)'
citation: 'Ruipeng Jia, Yanan Cao, Haichao Shi, Fang Fang, Pengfei Yin, Shi Wang: Flexible Non-Autoregressive Extractive Summarization with Threshold: How to Extract a Non-Fixed Number of Summary Sentences. AAAI 2021: 13134-13142'
---
Abstract
--
Sentence-level extractive summarization is a fundamental yet challenging task, and recent powerful approaches prefer to pick sentences sorted by the predicted probabilities until the length limit is reached, a.k.a. Top-K Strategy. This length limit is fixed based on the validation set, resulting in the lack of flexibility. In this work, we propose a more flexible and accurate non-autoregressive method for single document extractive summarization, extracting a non-fixed number of summary sentences without the sorting step. We call our approach ThresSum as it picks sentences simultaneously and individually from the source document when the predicted probabilities exceed a threshold. During training, the model enhances sentence representation through iterative refinement and the intermediate latent variables receive some weak supervision with soft labels, which are generated progressively by adjusting the temperature with a knowledge distillation algorithm. Specifically, the temperature is initialized with high value and drops along with the iteration until a temperature of 1. Experimental results on CNN/DM and NYT datasets have demonstrated the effectiveness of ThresSum, which significantly outperforms BERTSUMEXT with a substantial improvement of 0.74 ROUGE-1 score on CNN/DM. Our source code will be available on Github.

[Download paper here](https://ojs.aaai.org/index.php/AAAI/article/view/17552/17359)

