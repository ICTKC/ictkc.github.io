---
title: "Improving Bert Fine-Tuning via Stabilizing Cross-Layer Mutual Information"
collection: publications
permalink: /publication/23-icassp-jicunli
excerpt: ''
date: 2023-07-04
venue: 'ICASSP'
citation: 'Jicun Li, Xingjian Li, Tianyang Wang, Shi Wang, Yanan Cao, Chengzhong Xu, Dejing Dou. Improving Bert Fine-Tuning via Stabilizing Cross-Layer Mutual Information. In ICASSP 2023.'
---
Abstract
--
Fine-tuning pre-trained language models, such as BERT, has shown enormous success among various NLP tasks. Though simple and effective, the process of fine-tuning has been found unstable, which often leads to unexpected poor performance. To increase stability and generalizability, most existing works resort to maintaining the parameters or representations of pre-trained models during fine-tuning. Nevertheless, very little work explores mining the reliable part of pre-learned information that can help to stabilize fine-tuning. To address this challenge, we introduce a novel solution in which we fine-tune BERT with stabilized cross-layer mutual information. Our method aims to preserve the reliable behaviors of cross-layer information propagation, instead of preserving the information itself, of the pre-trained model. Therefore, our method circumvents the domain conflicts between pre-trained and target tasks. We conduct extensive experiments with popular pre-trained BERT variants on NLP datasets, demonstrating the universal effectiveness and robustness of our method.

[Download](https://ieeexplore.ieee.org/document/10095747)
[Download local](../files/23-icassp-jicunli.pdf)
