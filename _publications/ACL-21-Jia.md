---
title: "Deep Differential Amplifier for Extractive Summarization"
collection: publications
permalink: /publication/ACL-21-Jia
excerpt: 'For sentence-level extractive summarization, there is a disproportionate ratio of selected and unselected sentences, leading to flatting the summary features when maximizing the accuracy. In this paper, we conceptualize the single-document extractive summarization as a rebalance problem and present a deep differential amplifier framework. Specifically, we first calculate and amplify the semantic difference between each sentence and all other sentences, and then apply the residual unit as the second item of the differential amplifier to deepen the architecture. Finally, to compensate for the imbalance, the corresponding objective loss of minority class is boosted by a weighted cross-entropy. In contrast to previous approaches, this model pays more attention to the pivotal information of one sentence, instead of all the informative context modeling by recurrent or Transformer architecture. We demonstrate experimentally on two benchmark datasets that our summarizer performs competitively against state-of-the-art methods. Our source code will be available on Github.'
date: 2021-08-01
venue: 'Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers) (ACL-21)'
citation: 'Ruipeng Jia, Yanan Cao, Fang Fang, Yuchen Zhou, Zheng Fang, Yanbing Liu, Shi Wang: Deep Differential Amplifier for Extractive Summarization. ACL/IJCNLP (1) 2021: 366-376'
---
Abstract
--
For sentence-level extractive summarization, there is a disproportionate ratio of selected and unselected sentences, leading to flatting the summary features when maximizing the accuracy. The imbalanced classification of summarization is inherent, which cant be addressed by common algorithms easily. In this paper, we conceptualize the single-document extractive summarization as a rebalance problem and present a deep differential amplifier framework. Specifically, we first calculate and amplify the semantic difference between each sentence and all other sentences, and then apply the residual unit as the second item of the differential amplifier to deepen the architecture. Finally, to compensate for the imbalance, the corresponding objective loss of minority class is boosted by a weighted cross-entropy. In contrast to previous approaches, this model pays more attention to the pivotal information of one sentence, instead of all the informative context modeling by recurrent or Transformer architecture. We demonstrate experimentally on two benchmark datasets that our summarizer performs competitively against state-of-the-art methods. Our source code will be available on Github.

[Download paper here](https://aclanthology.org/2021.acl-long.31.pdf)

