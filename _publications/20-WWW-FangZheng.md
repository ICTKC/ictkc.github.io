---
title: "High Quality Candidate Generation and Sequential Graph Attention Network for Entity Linking"
collection: publications
permalink: /publication/WWW-20-FangZheng
excerpt: ''
date: 2020-04-20
venue: 'WWW (CCF-A)'
citation: 'Zheng Fang, Yanan Cao, Ren Li, Zhenyu Zhang, Yanbing Liu, Shi Wang: High Quality Candidate Generation and Sequential Graph Attention Network for Entity Linking. WWW 2020: 640-650'
---
Abstract
--
Entity Linking (EL) is a task for mapping mentions in text to corresponding entities in knowledge base (KB). This task usually includes candidate generation (CG) and entity disambiguation (ED) stages. Recent EL systems based on neural network models have achieved good performance, but they still face two challenges: (i) Previous studies evaluate their models without considering the differences between candidate entities. In fact, the quality (gold recall in particular) of candidate sets has an effect on the EL results. So, how to promote the quality of candidates needs more attention. (ii) In order to utilize the topical coherence among the referred entities, many graph and sequence models are proposed for collective ED. However, graph-based models treat all candidate entities equally which may introduce much noise information. On the contrary, sequence models can only observe previous referred entities, ignoring the relevance between the current mention and its subsequent entities. To address the first problem, we propose a multi-strategy based CG method to generate high recall candidate sets. For the second problem, we design a Sequential Graph Attention Network (SeqGAT) which combines the advantages of graph and sequence methods. In our model, mentions are dealt with in a sequence manner. Given the current mention, SeqGAT dynamically encodes both its previous referred entities and subsequent ones, and assign different importance to these entities. In this way, it not only makes full use of the topical consistency, but also reduce noise interference. We conduct experiments on different types of datasets and compare our method with previous EL system on the open evaluation platform. The comparison results show that our model achieves significant improvements over the state-of-the-art methods.

[Download paper here](../files/www20-High Quality Candidate Generation and Sequential Graph Attention Network for Entity Linking.pdf)

