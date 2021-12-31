---
title: "HIN: Hierarchical Inference Network for Document-Level Relation Extraction (BEST PAPER AWARD)"
collection: publications
permalink: /publication/PAKDD-20-TangHengzhu
excerpt: 'Document-level RE requires reading, inferring and aggregating over multiple sentences. From our point of view, it is necessary for document-level RE to take advantage of multi-granularity inference information: entity level, sentence level and document level. Thus, how to obtain and aggregate the inference information with different granularity is challenging for document-level RE, which has not been considered by previous work. In this paper, we propose a Hierarchical Inference Network (HIN) to make full use of the abundant information from entity level, sentence level and document level. Translation constraint and bilinear transformation are applied to target entity pair in multiple subspaces to get entity-level inference information. Next, we model the inference between entity-level information and sentence representation to achieve sentence-level inference information. Finally, a hierarchical aggregation approach is adopted to obtain the document-level inference information. In this way, our model can effectively aggregate inference information from these three different granularities. Experimental results show that our method achieves state-of-the-art performance on the large-scale DocRED dataset. We also demonstrate that using BERT representations can further substantially boost the performance.'
date: 2020-05-06
venue: 'Proceedings of the 2020 Conference on Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD-20)'
citation: 'Hengzhu Tang, Yanan Cao, Zhenyu Zhang, Jiangxia Cao, Fang Fang, Shi Wang, Pengfei Yin: HIN: Hierarchical Inference Network for Document-Level Relation Extraction. PAKDD (1) 2020: 197-209
'
---
Abstract
--
Sentence-level extractive text summarization is substantially a node classification task of network mining, adhering to the informative components and concise representations. There are lots of redundant phrases between extracted sentences, but it is difficult to model them exactly by the general supervised methods. Previous sentence encoders, especially BERT, specialize in modeling the relationship between source sentences. While, they have no ability to consider the overlaps of the target selected summary, and there are inherent dependencies among target labels of sentences. In this paper, we propose HAHSum (as shorthand for Hierarchical Attentive Heterogeneous Graph for Text Summarization), which well models different levels of information, including words and sentences, and spotlights redundancy dependencies between sentences. Our approach iteratively refines the sentence representations with redundancy-aware graph and delivers the label dependencies by message passing. Experiments on large scale benchmark corpus (CNN/DM, NYT, and NEWSROOM) demonstrate that HAHSum yields ground-breaking performance and outperforms previous extractive summarizers.

[Download paper here](https://link.springer.com/content/pdf/10.1007%2F978-3-030-47426-3_16.pdf)

