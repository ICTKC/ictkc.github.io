---
title: "Answer-focused and Position-aware Neural Question Generation"
collection: publications
permalink: /publication/EMNLP-18-Sun
excerpt: ''
date: 2018-10-29
venue: 'EMNLP'
citation: 'Xingwu Sun, Jing Liu, Yajuan Lyu, Wei He, Yanjun Ma, Shi Wang: Answer-focused and Position-aware Neural Question Generation. EMNLP 2018: 3930-3939'
---
Abstract
--
In this paper, we focus on the problem of question generation (QG). Recent neural network-based approaches employ the sequence-to-sequence model which takes an answer and its context as input and generates a relevant question as output. However, we observe two major issues with these approaches: (1) The generated interrogative words (or question words) do not match the answer type. (2) The model copies the context words that are far from and irrelevant to the answer, instead of the words that are close and relevant to the answer. To address these two issues, we propose an answer-focused and position-aware neural question generation model. (1) By answer-focused, we mean that we explicitly model question word generation by incorporating the answer embedding, which can help generate an interrogative word matching the answer type. (2) By position-aware, we mean that we model the relative distance between the context words and the answer. Hence the model can be aware of the position of the context words when copying them to generate a question. We conduct extensive experiments to examine the effectiveness of our model. The experimental results show that our model significantly improves the baseline and outperforms the state-of-the-art system.

[Download paper here](https://aclanthology.org/D18-1427/)
