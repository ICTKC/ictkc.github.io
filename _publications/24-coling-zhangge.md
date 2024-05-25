---
title: "CMDAG - A Chinese Metaphor Dataset with Annotated Grounds as CoT for Boosting Metaphor Generation"
collection: publications
permalink: /publication/24-coling-zhangge
excerpt: ''
date: 2024-05-04
venue: 'WSDM(CCF-B)'
citation: 'Yu Liu, Yanan Cao, Shi Wang, Qingyue Wang, Guanqun Bi. Generative Models for Complex Logical Reasoning over Knowledge Graphs.  WSDM 2024.'
---
Abstract
--
Answering complex logical queries over knowledge graphs (KGs) is a fundamental yet challenging task. Recently, query representation has been a mainstream approach to complex logical reasoning, making the target answer and query closer in the embedding space. However, there are still two limitations. First, prior methods model the query as a fixed vector, but ignore the uncertainty of relations on KGs. In fact, different relations may contain different semantic distributions. Second, traditional representation frameworks fail to capture the joint distribution of queries and answers, which can be learned by generative models that have the potential to produce more coherent answers. To alleviate these limitations, we propose a novel generative model, named DiffCLR, which exploits the diffusion model for complex logical reasoning to approximate query distributions. Specifically, we first devise a query transformation to convert logical queries into input sequences by dynamically constructing contextual subgraphs. Then, we integrate them into the diffusion model to execute a multi-step generative process, and a structure-enhanced self-attention is further designed for incorporating the structural features embodied in KGs. Experimental results on two benchmark datasets show our model effectively outperforms state-of-the-art methods, particularly in multi-hop chain queries with significant improvement.

[Download](https://dl.acm.org/doi/10.1145/3616855.3635804)
