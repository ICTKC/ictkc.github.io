---
title: "Enhancing Document Ranking with Task-adaptive Training and Segmented Token Recovery Mechanism"
collection: publications
permalink: /publication/EMNLP-21-Sun
excerpt: ''
date: 2021-12-01
venue: 'EMNLP (CCF-B)'
citation: 'Xingwu Sun, Yanling Cui, Hongyin Tang, Fuzheng Zhang, Beihong Jin, Shi Wang: Enhancing Document Ranking with Task-adaptive Training and Segmented Token Recovery Mechanism. EMNLP (1) 2021: 3570-3579'
---
Abstract
--
In this paper, we propose a new ranking model DR-BERT, which improves the Document Retrieval (DR) task by a task-adaptive training process and a Segmented Token Recovery Mechanism (STRM). In the task-adaptive training, we first pre-train DR-BERT to be domain-adaptive and then make the two-phase fine-tuning. In the first-phase fine-tuning, the model learns query-document matching patterns regarding different query types in a pointwise way. Next, in the second-phase fine-tuning, the model learns document-level ranking features and ranks documents with regard to a given query in a listwise manner. Such pointwise plus listwise fine-tuning enables the model to minimize errors in the document ranking by incorporating ranking-specific supervisions. Meanwhile, the model derived from pointwise fine-tuning is also used to reduce noise in the training data of the listwise fine-tuning. On the other hand, we present STRM which can compute OOV word representation and contextualization more precisely in BERT-based models. As an effective strategy in DR-BERT, STRM improves the matching perfromance of OOV words between a query and a document. Notably, our DR-BERT model keeps in the top three on the MS MARCO leaderboard since May 20, 2020.

[Download paper here](https://aclanthology.org/2021.emnlp-main.289/)

