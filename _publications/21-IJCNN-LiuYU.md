---
title: "Knowledge Enhanced Sequential Entity Linking"
collection: publications
permalink: /publication/IJCNN-21-LiuYu
excerpt: ''
date: 2021-07-18
venue: 'IJCNN'
citation: 'Yu Liu, Shi Wang, Kangli Zi, Jicun Li, Cungen Cao: Knowledge Enhanced Sequential Entity Linking. IJCNN 2021: 1-8'
---
Abstract
--
Entity Linking (EL) is the task of mapping mentions in texts to the corresponding entities in knowledge bases. Existing studies mostly focus on joint disambiguation based on the topical coherence, including graph and sequence models. Sequence models alleviate the complexity caused by graph models, but exist the error propagation that incorrectly disambiguated entities are likely to induce further errors when predicting future mentions. Moreover, it is a huge expense to construct the relationship between entities to explore structured knowledge. To address these problems, we propose a novel method, Knowledge Enhanced Sequential Entity Linking (KESEL), which converts global EL into a sequence decision problem and applies a pre-trained language model to better fuse entity knowledge. Specifically, we firstly utilize multiple features to learn local contextual representations of mentions and candidates respectively. Next, a sequential ERNIE model is introduced to generate knowledgeable representations by dynamically integrating the knowledge of previously referred entities into subsequent mentions disambiguation. Finally, by concatenating the above learned contextual and knowledgeable representations, we make full use of multi-semantic information to improve the performance of EL. Extensive experiments show that our method can achieve competitive or state-of-the-art results.

[Download paper here](../files/ijcnn21-Knowledge_Enhanced_Sequential_Entity_Linking.pdf)
[Source Code](https://github.com/ICTKC/KESEL)
