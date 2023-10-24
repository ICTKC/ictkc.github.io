---
title: "Divide, Conquer, and Combine: Mixture of Semantic-Independent Experts for Zero-Shot Dialogue State Tracking"
collection: publications
permalink: /publication/23-acl-qingyuewang
excerpt: ''
date: 2023-07-01
venue: 'ACL (CCF-A)'
citation: 'Qingyue Wang, Liang Ding, Yanan Cao, Yibing Zhan, Zheng Lin, Shi Wang, Dacheng Tao, and Li Guo. Divide, Conquer, and Combine: Mixture of Semantic-Independent Experts for Zero-Shot Dialogue State Tracking. In ACL 2023.'
---
Abstract
--
Zero-shot transfer learning for Dialogue State Tracking (DST) helps to handle a variety of task-oriented dialogue domains without the cost of collecting in-domain data. Existing works mainly study common data- or model-level augmentation methods to enhance the generalization but fail to effectively decouple semantics of samples, limiting the zero-shot performance of DST. In this paper, we present a simple and effective “divide, conquer and combine” solution, which explicitly disentangles the semantics of seen data, and leverages the performance and robustness with the mixture-of-experts mechanism. Specifically, we divide the seen data into semantically independent subsets and train corresponding experts, the newly unseen samples are mapped and inferred with mixture-of-experts with our designed ensemble inference.Extensive experiments on MultiWOZ2.1 upon T5-Adapter show our schema significantly and consistently improves the zero-shot performance, achieving the SOTA on settings without external knowledge, with only 10M trainable parameters.

[Download](https://aclanthology.org/2023.acl-long.114/)

