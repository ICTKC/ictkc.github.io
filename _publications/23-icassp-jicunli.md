---
title: "Improving Bert Fine-Tuning via Stabilizing Cross-Layer Mutual Information"
collection: publications
permalink: /publication/23-icassp-jicunli
excerpt: ''
date: 2023-07-01
venue: 'Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)'
citation: 'Qingyue Wang, Liang Ding, Yanan Cao, Yibing Zhan, Zheng Lin, Shi Wang, Dacheng Tao, and Li Guo. 2023. Divide, Conquer, and Combine: Mixture of Semantic-Independent Experts for Zero-Shot Dialogue State Tracking. In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 2048–2061, Toronto, Canada. Association for Computational Linguistics.'
---
Abstract
--
Fine-tuning pre-trained language models, such as BERT, has shown enormous success among various NLP tasks. Though simple and effective, the process of fine-tuning has been found unstable, which often leads to unexpected poor performance. To increase stability and generalizability, most existing works resort to maintaining the parameters or representations of pre-trained models during fine-tuning. Nevertheless, very little work explores mining the reliable part of pre-learned information that can help to stabilize fine-tuning. To address this challenge, we introduce a novel solution in which we fine-tune BERT with stabilized cross-layer mutual information. Our method aims to preserve the reliable behaviors of cross-layer information propagation, instead of preserving the information itself, of the pre-trained model. Therefore, our method circumvents the domain conflicts between pre-trained and target tasks. We conduct extensive experiments with popular pre-trained BERT variants on NLP datasets, demonstrating the universal effectiveness and robustness of our method.

[Download](https://ieeexplore.ieee.org/document/10095747)
[Download local](../files/23-icassp-jicunli.pdf)
